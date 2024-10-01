# Determinant
Let $A\in \mathcal{M}_{n}(F)$.
Define the following:
- the submatrix $A(i|j)\in \mathcal{M}_{m-1,n-1}(F)$ by deleting the $i$-th row and $j$-th column of $A$.
- the $(i,j)$-minor $M_{i,j}=\det A(i|j)$
- the $(i,j)$-cofactor $C_{i,j}\coloneqq(-1)^{i+j}M_{i,j}=(-1)^{i+j}\det A(i|j)$
- the cofactor matrix $C=[C_{i,j}]_{n\times n}$ of $A$.
- the adjugate matrix $\adj A=C\transpose$

Define $\det:\mathcal{M}_{n}(F)\to F$ by $\forall A\in\mathcal{M}_{n}(F):$
## Direct definitions
### Permutations
$\displaystyle \det A=\sum_{\sigma\in S_{n}}\sgn(\sigma)\prod_{i=1}^{n}[A]_{i,\sigma(i)}$
### Levi-Civita
$\displaystyle \det A=\sum_{(i_{1},\dots,i_{n})\in\ii{1}{n}^{n}}\varepsilon_{i_{1}\dots i_{n}}\prod_{k=1}^{n}[A]_{k,i_{k}}$
## Inductive definitions
### Adjugate product
$\det A=k$, where $k\in F$ is the value where $A\adj A=k I_{n}=\adj (A)A$
### Expand along row i
$$\begin{align}
\det A&=[A\adj A]_{i,i} \\
&=[A]_{i,\cdot}[\adj A]_{\cdot,i}=\sum_{j=1}^{n}[A]_{i,j}[\adj A]_{j,i} \\
&=[A]_{i,\cdot}\begin{bmatrix}C_{i,1} \\ \vdots \\ C_{i,n}\end{bmatrix}=\sum_{j=1}^{n}[A]_{i,j}C_{i,j}=\sum_{j=1}^{n}(-1)^{i+j}[A_{i,j}]M_{i,j} \\
&=\sum_{j=1}^n (-1)^{i+j}[A]_{i,j}\det(A(i|j))
\end{align}$$
### Expand along column j
$$\begin{align}
\det A&=[\adj (A)A]_{j,j} \\
&=[\adj A]_{j,\cdot}[A]_{\cdot,j}=\sum_{i=1}^{n}[\adj A]_{j,i}[A]_{i,j} \\
&=\begin{bmatrix}C_{1,j} & \cdots & C_{n,j}\end{bmatrix}[A]_{\cdot,j}=\sum_{i=1}^{n}C_{i,j}[A]_{i,j}=\sum_{i=1}^{n}(-1)^{i+j}[A_{i,j}]M_{i,j} \\
&=\sum_{i=1}^n (-1)^{i+j}[A]_{i,j}\det(A(i|j))
\end{align}$$
## Non-constructive
$\det A=\delta(A)$, where $\delta:\mathcal{M}_{n}(F)\cong(F^{n})^{n}\to F$ is the unique alternating $n$-linear map satisfying $\delta(I_{n})=1$ in terms of the matrix's columns or rows.
## Eigenvalue
(Assuming the characteristic polynomial of $A$ splits over $F$)
$\displaystyle \det A=\prod_{i=1}^{m}\lambda_{i}^{\mu_{A}(\lambda_{i})}=\prod_{i=1}^{n}\lambda_{i}'$. where $\rho (A)=\set{\lambda_{i}:\mu_{A}(\lambda_{i})\given i\in\ii{1}{m}}=\set{\lambda_{i}'}_{i=1}^{n}$.