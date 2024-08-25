Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 2.3.1 (Transition map is a diffeomorphism)
Let $S$ be a regular surface and $p\in S$.
Let $\varphi_{1}: U_{1}\to V_{1}$ and $\varphi_{2}:U_{2}\to V_{2}$ be two parametrizations of $S$ at $p$.
Let $U_{1}'=\varphi_{1}^{-1}(V_{1}\cap V_{2}),U_{2}'=\varphi_{2}^{-1}(V_{1}\cap V_{2})$.
Let $\psi_{12}:U_{1}'\to U_{2}'$ be $\psi_{12}=\varphi_{2}^{-1}\circ \varphi_{1}$ on $U_{1}'$.
Then $\psi_{12}$ is a diffeomorphism.
#### Proof
Note that $\psi_{21}\coloneqq \varphi_{1}^{-1}\circ \varphi_{2}:U_{2}'\to U_{1}'$ is a continuous inverse of $\psi_{12}$.
Hence $\psi_{12}$ is a homeomorphism.
Since $S$ is locally a graph, WLOG, suppose over $xy$-plane.
Let $\pi:\mathbb{R}^{3}\to \mathbb{R}^{2}$ be the projection map onto $xy$-plane.
Then $\psi_{12}=\varphi_{2}^{-1}\circ \varphi_{1}=(\pi \circ \varphi_{2})^{-1}\circ(\pi \circ \varphi_{1})$ on $U_{1}'$.
Similarly, $\psi_{21}=\varphi_{1}^{-1}\circ \varphi_{2}=(\pi \circ \varphi_{1})^{-1}\circ (\pi \circ \varphi_{2})$ on $U_{2}'$.
Since both are composites of differentiable functions, they are differentiable.