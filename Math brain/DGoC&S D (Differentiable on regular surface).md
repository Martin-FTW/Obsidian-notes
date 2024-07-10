Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Differentiable on regular surface)
Let $S$ be a regular surface and $V$ be open in $S$.
Let $f:V\to \mathbb{R}^{m}$ be a function.
We call $f$ differentiable at $p\in V$ if the following equivalent statements hold:
- $\forall$ parametrization $\varphi:U\to V$ with $p\in \varphi(U)$, $f\circ \varphi:U\to \mathbb{R}^{m}$ is differentiable at $\varphi ^{-1}(p)$
- $\exists$ parametrization $\varphi:U\to V$ with $p\in \varphi(U)$ s.t. $f\circ \varphi:U\to \mathbb{R}^{m}$ is differentiable at $\varphi ^{-1}(p)$

We call $f$ differentiable on $V$ if the following equivalent statements hold:
- $\forall p\in V:f$ is differentiable at $p$
- $\forall$ parametrization $\varphi:U\to V$, $f\circ \varphi:U\to \mathbb{R}^{m}$ is differentiable
- $\exists$ parametrization $\varphi:U\to V$ s.t. $f\circ \varphi:U\to \mathbb{R}^{m}$ is differentiable.

All equivalences are given by [[DGoC&S P 2.3.1 (Transition map is a diffeomorphism)]]

Now let $S_{1},S_{2}$ be regular surfaces.
Let $g:S_{1}\to S_{2}$ be a function.
We call $g$ differentiable if
- $\forall$ parametrization $\varphi_{1}:U_{1}\to S_{1}$, $g\circ \varphi_{1}:U_{1}\to S_{2}$ is differentiable
- $\exists$ parametrization $\varphi_{1}:U_{1}\to S_{1}$ s.t. $g\circ \varphi_{1}:U_{1}\to S_{2}$ is differentiable