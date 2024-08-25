Book: [[Tu An Introduction to Manifolds (AItM)]]
# Theorem 9.9 (Regular set theorem)
Let $N,M$ be manifolds of dimension $n,m$ respectively.
Let $F:N\to M$ be a smooth map.
Let $S=F^{-1}(c)$ be a nonempty regular level set.
Then $S$ is a regular submanifold of $N$ of codimension $m$.
#### Proof
Let $(V,\psi)=(V,y^{1},\dots,y^{m})$ be a chart of $M$ cenetered at $c$.
Since $F$ is continuous, $F^{-1}(V)$ is an open set in $N$ with $F^{-1}(V)\supseteq S$.
Since $S=F^{-1}(c)=(\psi \circ F)^{-1}(\vec{0})$, we have $S$ is the zero set of $\psi \circ F$.
Denote $F^{i}=y^{i}\circ F=r^{i}\circ \psi \circ F$
Since $S$ is nonempty, we have $F$ is a submersion at every point on $S$, thus $n\geq m$.
Let $p\in S$ and let $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart about $p$ in $N$.
WLOG, suppose $U\subseteq F^{-1}(V)$.
Since $c$ is a regular value of $F$, we have $p$ is a regular point of $F$, thus $\displaystyle \rank\left[ \frac{ \partial F^{i}}{ \partial x^{j} }(p) \right]=m$.
By renumbering the $F^{i}$ and $x^{j}$, we can assume the first $m\times m$ block $\displaystyle \left[ \frac{ \partial F^{i}}{ \partial x^{j} } (p)\right]_{i,j\in\ii{1}m{}}$ is nonsingular. 
Now $\displaystyle\det\begin{bmatrix}\dfrac{ \partial F^{i}}{ \partial x^{j} }& \dfrac{ \partial F^{i}}{ \partial x^{\beta} }\\\dfrac{ \partial F^{\alpha}}{ \partial x^{j} }&\dfrac{ \partial x^{\alpha}}{ \partial x^{\beta} }\end{bmatrix}_{\substack{1\leq i,j\leq m\\m+1\leq \alpha,\beta \leq n}}=\det\begin{bmatrix}\dfrac{ \partial F^{i}}{ \partial x^{j} }& \dfrac{ \partial F^{i}}{ \partial x^{\beta} }\\ 0_{n-m,m}& I_{n-m}\end{bmatrix}=\det\left[ \frac{ \partial F^{i}}{ \partial x^{j} } \right]\neq 0$
Hence $\exists$ nbhd $U_{p}\subseteq U$ of $p$ s.t. $(U_{p},F^{1},\dots,F^{m},x^{m+1},\dots x^{n})$ is a chart in the atlas of $N$.
Now every point $p\in S$ has an adapted chart for $N$ relative to $S$.
Thus $S$ is a regular submanifold of $N$ of codimension $m$.