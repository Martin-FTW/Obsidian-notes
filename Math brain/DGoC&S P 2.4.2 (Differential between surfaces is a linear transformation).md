Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 2.4.2 (Differential between surfaces is a linear transformation)
Assume the notation in [[DGoC&S D (Differential between surfaces)]].
Then $df_{p}:T_{p}S_{1}\to T_{f(p)}S_{2}$ is a well-defined linear transformation, i.e.
1. $\beta'(0)$ is independent of the choice of $\alpha$, and
2. $df_{p}$ is linear.
#### Proof
Let $\varphi(u,v)$ be a parametrization of $S_{1}$ at $p$, and $\bar{\varphi}(\bar{u},\bar{v})$ be a parametrization of $S_{2}$ at $f(p)$.
If $\alpha(t)=(u(t),v(t))$, then $\beta(t)=f \circ \alpha(t)=(f_{1}(u(t),v(t)),f_{2}(u(t),v(t)))$.
Hence in the basis $\set{\bar{\varphi}_{\bar{u}}(f(p)),\bar{\varphi}_{\bar{v}}(f(p))}$, we have $$\beta'(0)=\left( \frac{ \partial f_{1} }{ \partial u }u'(0)+\frac{ \partial f_{1} }{ \partial v }v'(0),\frac{ \partial f_{2} }{ \partial u }u'(0)+\frac{ \partial f_{2} }{ \partial v }v'(0) \right)$$
Since it depends only on $\alpha'(0)$ and $\alpha(0)$, $\beta'(0)$ is independent of $\alpha$.
Now $\beta'(0)=df_{p}(w)=\begin{bmatrix}\frac{ \partial f_{1} }{ \partial u }&\frac{ \partial f_{1} }{ \partial v }\\\frac{ \partial f_{2} }{ \partial u }&\frac{ \partial f_{2} }{ \partial v }\end{bmatrix}\begin{bmatrix}u'(0)\\ v'(0)\end{bmatrix}$ by above.
Hence $[df_{p}]_{\set{\varphi_{u},\varphi_{v}}}^{\set{\bar{\varphi}_{\bar{u}},\bar{\varphi}_{\bar{v}}}}$ is the matrix above, thus is linear.