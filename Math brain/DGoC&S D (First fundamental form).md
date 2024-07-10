Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (First fundamental form)
Let $S$ be a regular surface and $p\in S$.
Since $T_{p}S$ is a subspace of $\mathbb{R}^{3}$, it inherits an inner product $\innerp{\cdot}{\cdot}{p}$.
Define positive-definite symmetric bilinear form on $T_{p}S$ by $\fff_{p}(u,v)=g_{p}(u,v)=\innerp{u}{v}{p}=\innerp{u}{v}{\mathbb{R}^{3}}$.
We call $\fff_{p}$ or $g_{p}$ the first fundamental form of $S$ at $p$.

Note that given a parametrization $\varphi:U\to S$ at $p$, we have basis $\beta=\set{\varphi_{u},\varphi_{v}}$ for $T_{p}S$.
Thus $\psi_{\beta}(g_{p})=\begin{bmatrix}g_{p}(\varphi_{u},\varphi_{u})&g_{p}(\varphi_{u},\varphi_{v})\\g_{p}(\varphi_{u},\varphi_{v})&g_{p}(\varphi_{v},\varphi_{v})\end{bmatrix}$
Denote 
- $E(u_{0},v_{0})=g_{11}(u_{0},v_{0})=g_{p}(\varphi_{u}(u_{0},v_{0}),\varphi_{u}(u_{0},v_{0}))$
- $F(u_{0},v_{0})=g_{12}(u_{0},v_{0})=g_{p}(\varphi_{u}(u_{0},v_{0}),\varphi_{v}(u_{0},v_{0}))$
- $G(u_{0},v_{0})=g_{22}(u_{0},v_{0})=g_{p}(\varphi_{v}(u_{0},v_{0}),\varphi_{v}(u_{0},v_{0}))$

