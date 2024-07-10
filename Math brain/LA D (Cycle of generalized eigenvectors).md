Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Cycle of generalized eigenvectors)
Let $T$ be a linear operator on a vector space $V$.
Let $x$ be a generalized eigenvector of $T$ corresponding to eigenvalue $\lambda$.
Suppose $p=\min \set{p\given(T-\lambda I)^{p}(x)=0}$.
Then the ordered set $\set{(T-\lambda I)^{p-1}(x),\dots,(T-\lambda I)(x),x}$ is called a cycle of generalized eigenvectors of $T$ corresponding to $\lambda$.
The vector $(T-\lambda I)^{p-1}(x)$ is called the initial vector of the cycle
The vector $x$ is called the end vector of the cycle
We say that the length of the cycle is $p$.