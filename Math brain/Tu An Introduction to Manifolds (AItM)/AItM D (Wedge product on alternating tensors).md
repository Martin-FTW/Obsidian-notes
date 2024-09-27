Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Wedge product on alternating tensors)
Let $V$ be a vector space.
Let $f\in A_{k}(V),g\in A_{\ell}(V)$
We define the wedge product $f\wedge g=\dfrac{1}{k!\ell!}A(f\otimes g)\in A_{k+\ell}(V)$.
Explicitly, $\begin{align}\displaystyle (f\wedge g)(v_{1},\dots,v_{k+\ell})&=\frac{1}{k!\ell!}\sum_{\sigma\in S_{k+\ell}}(\sgn \sigma)f(v_{\sigma(1)},\dots,v_{\sigma(k)})g(v_{\sigma(k+1)},\dots,v_{\sigma(k+\ell)})\\&=\sum_{\sigma\in S_{(k,\ell)}}(\sgn \sigma)f(v_{\sigma(1)},\dots,v_{\sigma(k)})g(v_{\sigma(k+1)},\dots,v_{\sigma(k+\ell)})\end{align}$, where $S_{(k,\ell)}=\set{\sigma\in S_{k+\ell}\given \sigma(1)<\cdots<\sigma(k)\land \sigma(k+1)<\cdots<\sigma(k+\ell)}$ is the set of all $(k,\ell)$-shuffles.