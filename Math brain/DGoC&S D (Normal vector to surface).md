Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Normal vector to surface)
Let $S$ be a regular surface and $p\in S$.
A nonzero vector $N$ at $p$ is called a normal vector of $S$ at $p$ if $\forall v\in T_{p}S:N\perp v$.
## Local param
If $\varphi:U\to S$ is a parametrization of $S$ at $p$, then $T_{p}S=\span \set{\varphi_{u}(q),\varphi_{v}(q)}$ where $\varphi(q)=p$.
One choice of $N$ is $N=\varphi_{u}(q)\times \varphi_{v}(q)$.
Thus $N=\left.\dfrac{\varphi_{u}\times \varphi_{v}}{\norm{\varphi_{u}\times \varphi_{v}}}\right\vert_{q}$ is a unit normal to $S$ at $p$.
## Level surface
If $S=F^{-1}(\set{c})$ is a level surface, where $F$ is differentiable and $c$ is a regular value of $F$, then
$N=\dfrac{\nabla F}{\norm{\nabla F}}$ is a unit normal to $S$ at $p$.