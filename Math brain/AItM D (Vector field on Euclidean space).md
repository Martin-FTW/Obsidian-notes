Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Vector field on Euclidean space)
Let $U\subseteq \mathbb{R}^{n}$ be open.
Let $X:U\to T_{p}(\mathbb{R}^{n})$ be a function denoted by $X(p)=X_{p}$.
We call any such $X$ a vector field on $U$.
Since $T_{p}(\mathbb{R}^{n})$ has $\displaystyle \set*{\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}}$ as basis, we have the linear combination $X_{p}=\sum a^{i}(p)\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$ for $p\in U,a^{i}(p)\in \mathbb{R}$.
We call $a^{i}$ the coefficient functions of $X$.
We call $X$ a $C^{\infty}$ vector field if all its coefficient functions $a^{i}$ are $C^{\infty}$ on $U$.
We denote the set of all $C^{\infty}$ vector fields by $\mathfrak{X}(U)$. Note that it is a vector space over $\mathbb{R}$.
Omitting $p$, we make the identification with column vectors of $C^{\infty}$ functions on $U$:
$\displaystyle X=\sum a^{i}\frac{ \partial }{ \partial x^{i} }\leftrightarrow \begin{bmatrix}a^1\\\vdots\\a^n\end{bmatrix}$

Define scalar multiplication of $f\in C^{\infty}(U),X\in \mathfrak{X}(U)$ by their pointwise product $(fX)_{p}=f(p)X_{p}$ for $p\in U$.
This makes $\mathfrak{X}(U)$ into a vector module over the ring $C^{\infty}(U)$.