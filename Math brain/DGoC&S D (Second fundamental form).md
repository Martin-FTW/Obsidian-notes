Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Second fundamental form)
Let $S$ be a regular surface and $p\in S$.
Define a bilinear form $\sff_{p}$ on $T_{p}S$ by $\sff_{p}(v,w)\innerp{S_{p}(v)}{w}{}$.
We call $\sff$ the second fundamental form of $S$ at $p$.
Note that this is a well-defined symmetric bilinear form by [[DGoC&S P 3.2.1 (The shape operator is self-adjoint)]].

Given a parametrization $\varphi:U\to S$ at $p$, we have a basis $\set{\varphi_{u},\varphi_{v}}$ for $T_{p}S$, as well as the unit normal $N=\frac{\varphi_{u}\times \varphi_{v}}{\norm{\varphi_{u}\times \varphi _{v}}}$.
We denote {shorthands: $\varphi_{?}\to \varphi_{?}(p),N_{?}\to N_{?}(p)\to(N\circ \varphi)_{?}(p)$}:
- $e=\sff_{p}(\varphi_{u},\varphi_{u})=\innerp{S_{p}(\varphi_{u})}{\varphi_{u}}{}=\innerp{-N_{u}}{\varphi_{u}}{}=\innerp{N}{\varphi_{uu}}{}$
- $f=\sff_{p}(\varphi_{u},\varphi_{v})=\innerp{S_{p}(\varphi_{u})}{\varphi_{v}}{}=\innerp{-N_{u}}{\varphi_{v}}{}=\innerp{N}{\varphi_{uv}}{}$
- $g=\sff_{p}(\varphi_{v},\varphi_{v})=\innerp{S_{p}(\varphi_{v})}{\varphi_{v}}{}=\innerp{-N_{v}}{\varphi_{v}}{}=\innerp{N}{\varphi_{vv}}{}$

Alternative notation: $A_{p}=\sff_{p}, [A_{ij}]=\psi_{\set{\varphi_{u},\varphi_{v}}}[\sff_{p}]$