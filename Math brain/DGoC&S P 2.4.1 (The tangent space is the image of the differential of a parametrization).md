Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 2.4.1 (The tangent space is the image of the differential of a parametrization)
Let $S$ be a regular surface.
Let $\varphi:U\to S$ be a parametrization and $q\in U$.
Then $T_{\varphi(q)}S=d\varphi_{q}(\mathbb{R}^{2})=\span \set*{\dfrac{ \partial \varphi }{ \partial u }(q),\dfrac{ \partial \varphi }{ \partial v }(q)  }$.
#### Proof
Let $v\in T_{\varphi(q)}S$. Then $\exists \alpha:(-\epsilon,\epsilon)\to S$ s.t. $\alpha(0)=\varphi(q),\alpha'(0)=v$.
Since $U$ is open, we can assume $\alpha$ lies in $\varphi(U)$ by taking smaller $\epsilon$.
Now let $\beta:(-\epsilon,\epsilon)\to U$ be $\beta=\varphi ^{-1}\circ \alpha$, thus $\alpha=\varphi \circ \beta$.
Hence $v=\alpha'(0)=(d\varphi_{\alpha(0)}\circ \beta')(0)=d\varphi_{q}(\beta'(0))\in d\varphi_{q}(\mathbb{R}^{2})$ by chain rule.
More explicitly, if $\beta(t)=(u(t),v(t))$, we have
$v=\alpha'(0)=\dfrac{d(\varphi \circ(u,v))}{dt}(0)=\varphi_{u}(q)u'(0)+\varphi_{v}(q)v'(0)\in\span \set*{\dfrac{ \partial \varphi }{ \partial u }(q),\dfrac{ \partial \varphi }{ \partial v }(q)  }$.

Conversely, let $w\in d\varphi_{q}(\mathbb{R}^{2})$. Then $\exists v\in \mathbb{R}^{2}$ s.t. $w=d\varphi_{q}(v)$.
Now let $\gamma:(-\epsilon,\epsilon)\to U$ be $\gamma(t)=q+tv$ for any $t\in(\epsilon,\epsilon)$.
Finally let $\alpha:(-\epsilon,\epsilon)\to S$ be $\alpha=\varphi \circ \gamma$.
Then $\alpha(0)=q$ and $\alpha'(0)=(d\varphi_{\alpha(0)}\circ\gamma')(0)=d\varphi_{q}(\gamma'(0))=d\varphi_{q}(v)$.
Hence $w\in T_{\varphi(q)}S$.