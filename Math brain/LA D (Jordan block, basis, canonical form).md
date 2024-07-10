Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Jordan block, basis, canonical form)
Let $T$ be a linear operator on a finite-dimensional vector space $V$.
Suppose the characteristic polynomial of $T$ splits.
Let $\lambda$ be an eigenvalue of $T$.
Let $A_{ij}=\begin{cases}\lambda & \text{if }i=j \\1&\text{if } j=i+1\\0&\text{otherwise}\end{cases}$
Then $A=(A_{ij})$ is called a Jordan block corresponding to $\lambda$.
Let $\beta$ be an ordered basis for $V$ such that $\exists$ Jordan blocks $A_{1},\dots,A_{k}$ s.t. $$[T]_{\beta}=\begin{bmatrix}
A_{1} & O & \cdots & O \\
O & A_{2} & \cdots & O  \\
\vdots & \vdots & \ddots & \vdots \\
O & O & \cdots & A_{k}
\end{bmatrix}$$
Then $\beta$ is called a Jordan canonical basis for $T$ and $[T]_{\beta}$ is called a Jordan canonical form of $T$.

Let $A\in M_{n\times n}(F)$ be a matrix whose characteristic polynomial splits.
Then the Jordan canonical form of $A$ is defined to be the Jordan canonical form of $L_{A}$.