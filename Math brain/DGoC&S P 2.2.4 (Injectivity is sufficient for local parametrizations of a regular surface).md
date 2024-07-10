Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 2.2.4 (Injectivity is sufficient for local parametrizations of a regular surface)
Let $S$ be a regular surface and $p\in S$.
Let $U\subseteq \mathbb{R}^{2}$ be open.
Let $\varphi:U\to \mathbb{R}^{3}$ be a function s.t. $p\in\varphi(U)\subseteq S$.
Suppose $\varphi$ is differentiable and the regularity condition holds.
Now if $\varphi$ is injective, then $\varphi ^{-1}:\varphi(U)\to U$ is continuous.
In this case, we have $\varphi$ is a differentiable homeomorphism.
#### Proof
Let $q\in U$. Then $\exists$ $2\times2$ submatrix of the jacobian that is invertible.
WLOG, suppose $\det \frac{ \partial (x,y) }{ \partial (u,v) }\neq 0$ and swap coordinate axis otherwise.
Let $\pi:\mathbb{R}^{3}\to \mathbb{R}^{2}$ be $\pi(x,y,z)=(x,y)$.
Then by inverse function theorem, $\pi \circ \varphi$ is a local diffeomorphism.
i.e. $\exists$ nbhd $V_{1}$ of $q$ in $U$ and nbhd $V_{2}$ of $\pi \circ \varphi(q)$ in $\mathbb{R}^{2}$ s.t. $\pi \circ \varphi$ is a diffeomorphism between $V_{1},V_{2}$.
Now since $\varphi|_{U}^{\varphi(U)}$ is bijective, we have $\varphi|_{V_{1}}^{-1}=(\pi \circ \varphi)^{-1}\circ \pi$, thus is continuous.