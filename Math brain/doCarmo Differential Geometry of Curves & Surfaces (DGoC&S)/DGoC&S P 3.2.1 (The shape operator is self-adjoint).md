Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 3.2.1 (The shape operator is self-adjoint)
Let $S$ be a regular surface with orientation $N$.
The shape operator $S_{p}:T_{p}S\to T_{N(p)}\mathbb{S}^{2}\cong N(p)^{\perp}=T_{p}S$ is self-adjoint.
To be precise, $\exists$ isomorphism $\varphi:T_{N(p)}\mathbb{S}^{2}\to T_{p}S$ s.t. $\varphi \circ S_{p}:T_{p}S\to T_{p}S$ is self-adjoint.
#### Proof
For the isomorphism, note that from $\norm{N(t)}=1$ for all $t$, we have $\innerp{N(\alpha(t))}{(N\circ \alpha)'(t)}{}=0$ for all $t,\alpha$.
Thus $\innerp{N(p)}{S_{p}(v)}{}=0$ for all $v\in T_{p}S$.
It follows that $S_{p}(v)\in N(p)^{\perp}=T_{p}S$.

Now let $\varphi:U\to S$ be a parametrization of $S$ at $p$.
Then $\set{\varphi_{u},\varphi_{v}}$ is a basis for $T_{p}S$. 
If $\alpha:(-\varepsilon,\varepsilon)\to S$ is a differentiable curve with $\alpha(0)=p$, then we can write $\alpha(t)=\varphi(u(t),v(t))$, thus we have $$\begin{align}
dN_{p}(\alpha'(0))&=dN_{p}(\varphi_{u}(p)u'(0)+\varphi_{v}(p)v'(0)) \\
&=\left. \frac{d(N\circ(u,v))}{dt} \right|_{t=0} \\
&=N_{u}u'(0)+N_{v} v'(0)
\end{align}$$  
In particular, we have $dN_{p}(\varphi_{u}(p))=N_{u}$ and $dN_{p}(\varphi_{v}(p))=N_{v}$.
Thus it suffices to show $\innerp{N_{u}}{\varphi_{v}}{}=\innerp{\varphi_{u}}{N_{v}}{}$ as $dN_{p}$ is linear.
Since $\innerp{N}{\varphi_{u}}{}=0=\innerp{N}{\varphi_{v}}{}$, we have $0=\frac{ \partial }{ \partial v }\innerp{N}{\varphi_{u}}{}=\innerp{N_{v}}{\varphi_{u}}{}+\innerp{N}{\varphi_{uv}}{}$ and $0=\frac{ \partial }{ \partial u }\innerp{N}{\varphi_{v}}{}=\innerp{N_{u}}{\varphi_{v}}{}+\innerp{N}{\varphi_{vu}}{}$
Since $\varphi$ is smooth, in particular $C^{2}$, we have $\varphi_{uv}=\varphi_{vu}$, thus $\innerp{N_{u}}{\varphi_{v}}{}=-\innerp{N}{\varphi_{uv}}{}=\innerp{N_{v}}{\varphi_{u}}{}$
Hence $dN_{p}:T_{p}S\to T_{p}S$ is self-adjoint.