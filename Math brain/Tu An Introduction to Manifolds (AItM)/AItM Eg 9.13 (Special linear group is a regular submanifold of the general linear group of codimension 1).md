Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 9.13 (Special linear group is a regular submanifold of the general linear group of codimension 1)
Note that $\SL(n,\mathbb{R})$ is a subgroup of $\GL(n,\mathbb{R})$.
Now we apply the regular set theorem to $\det$ since $\SL(n,\mathbb{R})=\det ^{-1}(1)$.
Since $\displaystyle \det(A)=\sum_{j=1}^{n}(-1)^{i+j}a_{ij}m_{ij}$, we have $\displaystyle \frac{ \partial \det}{ \partial a^{ij} }=(-1)^{i+j}m_{ij}$.
Now $A$ is a critical point of $f$ iff all $m_{ij}$ are $0$, which implies that $\det A=0$.
Since all matrices in $\SL(n,\mathbb{R})$ has $\det A=1$, we have $1$ is a regular value of $\det$.
Thus by [[AItM T 9.9 (Regular set theorem)]], we have $\SL(n,\mathbb{R})$ is a regular submanifold of $\GL(n,\mathbb{R})$ with codimension $1$.