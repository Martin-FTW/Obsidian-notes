Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 2.6.1 (Orientable iff a differentiable unit normal vector field exists)
Let $S$ be a regular surface.
Then $S$ is orientable iff $\exists$ differentiable unit normal vector field $N:S\to \mathbb{R}^{3}$ of $S$, i.e. $\forall p\in S:T_{p}S\perp N(p)$ and $\norm{N(p)}=1$.
In particular, the normal vectors are defined by $N=\dfrac{\varphi_{u}\times \varphi_{v}}{\norm{\varphi_{u}\times \varphi_{v}}}$.
#### Proof
$(\implies):$ Suppose $S$ is orientable. Then $\exists$ orientation $\set{\varphi_{\alpha}}$ of $S$.
Now $\forall p\in S$, $\exists \alpha_{p}$ s.t. $p=\varphi_{\alpha_{p}}(u,v)$, let $N(p)=\dfrac{\frac{ \partial \varphi_{\alpha_{p}} }{ \partial u }\times \frac{ \partial \varphi_{\alpha_{p}} }{ \partial v }}{\norm*{{\frac{ \partial \varphi_{\alpha_{p}} }{ \partial u }\times \frac{ \partial \varphi_{\alpha_{p}} }{ \partial v }}}}(u,v)$.
Well-defined: Suppose $p=\varphi(u,v)=\overline{\varphi}(\overline{u},\overline{v})$ are two parametrizations.
Let $\psi=\varphi ^{-1}\circ \overline{\varphi}$ be the transition map. Then $J\overline{\varphi}(\overline{u},\overline{v})=J\varphi(u,v)J\psi(\overline{u},\overline{v})$.
Then $\overline{\varphi}_{\overline{u}}\times \overline{\varphi}_{\overline{v}}(\overline{u},\overline{v})=(\varphi_{u}\times \varphi_{v})\det\dfrac{ \partial (u,v) }{ \partial (\overline{u},\overline{v}) }$.
Since $\set{\varphi_{\alpha}}$ is an orientation, the jacobian determinant is positive.
Thus the unit vectors are equal, i.e. $N(p)$ is independent of the choice of parametrization.
Now $N$ is a differentiable field of unit normal vectors on $S$.
$(\impliedby):$ Suppose $N:S\to \mathbb{R}^{3}$ exists.
WLOG, assume $S$ has only 1 connected component.
Cover $S$ by the parametrizations $\set{\varphi^{\alpha}}$.
For each $\alpha$, define $f_{\alpha}:\varphi^{\alpha}(U_{\alpha})\to \set{\pm 1}$ by $f_{\alpha}(p)=\innerp*{N(p)}{\dfrac{\varphi^{\alpha}_{u}\times \varphi^{\alpha}_{v}}{\norm{\varphi^{\alpha}_{u}\times \varphi^{\alpha}_{v}}}}{}$.
Since $N$ is continuous, we have either $f_{\alpha}\equiv 1$ or $f_{\alpha}\equiv -1$.
By swapping $u,v$, we can WLOG assume $f_{\alpha}\equiv 1$.
Since both entries of the inner product are unit vectors, we have $N(p)=\dfrac{\varphi^{\alpha}_{u}\times \varphi^{\alpha}_{v}}{\norm{\varphi^{\alpha}_{u}\times \varphi^{\alpha}_{v}}}$.
Now at the intersection of any two coordinate nbhds $U_{\alpha},U_{\alpha'}$, we have $\dfrac{\varphi^{\alpha}_{u}\times \varphi^{\alpha}_{v}}{\norm{\varphi^{\alpha}_{u}\times \varphi^{\alpha}_{v}}}=\dfrac{\varphi^{\alpha'}_{\overline{u}}\times \varphi^{\alpha'}_{\overline{v}}}{\norm{\varphi^{\alpha'}_{\overline{u}}\times \varphi^{\alpha'}_{\overline{v}}}}$.
Hence $\det\left( \dfrac{ \partial (u,v) }{ \partial (\overline{u},\overline{v}) } \right)>0$ (otherwise $N(p)=-N(p)$).