Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 6.23 (Jacobian of smooth maps between manifolds)
Let $N,M$ be manifolds of dimensions $n,m$ respectively..
Let $F:N\to M$ be a smooth map.
Let $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart on $N$ and $(V,\psi)=(V,y^{1},\dots,y^{n})$ be a chart on $M$ such that $F(U)\subseteq V$.
Denote $F^{i}\coloneqq y^{i}\circ F=r^{i}\circ \psi \circ F:U\to \mathbb{R}$.
The matrix $\displaystyle\left[ \frac{ \partial F^{i} }{ \partial x^{j} } \right]_{m\times n}$ is called the Jacobian matrix of $F$ relative to $(U,\phi)$ and $(V,\psi)$.
Now suppose $n=m$.
Then we call $\displaystyle \frac{ \partial (F^{1},\dots,F^{n}) }{ \partial (x^{1},\dots,x^{n}) }\coloneqq \det\left[ \frac{ \partial F^{i}}{ \partial x^{j} } \right]$ the Jacobian determinant of $F$ relative to $(U,\phi)$ and $(V,\psi)$
