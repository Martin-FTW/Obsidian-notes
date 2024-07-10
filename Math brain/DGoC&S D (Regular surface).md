Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Regular surface)
Let $S\subseteq \mathbb{R}^{3}$.
We call $S$ a regular surface if 
- $\forall p\in S:\exists$ open $U\subseteq \mathbb{R}^{2}$ and nbhd $V$ of $p$ in $S$ s.t.
	- $\exists C^{\infty}$ homeomorphism $\varphi:U\to V$ satisfying the following equivalent statements called the regularity condition:
		- $\forall q\in U$, $d\varphi|_{q}:\mathbb{R}^{2}\to \mathbb{R}^{3}$ is injective.
		- $\forall q\in U$, $\set*{\dfrac{ \partial \varphi }{ \partial u } ,\dfrac{ \partial \varphi }{ \partial v } }$ is linearly independent
		- $\forall q\in U$, $\varphi_{u}(q)\times \varphi_{v}(q)\neq 0$
		- $\rank(d\varphi|_{q})=\rank J\varphi|_{q}=2$
		- $\exists$ $2\times 2$ submatrix of $Jf|_{q}$ that is invertible.
		- One of $\frac{ \partial (x,y) }{ \partial (u,v) },\frac{ \partial (y,z) }{ \partial (u,v) },\frac{ \partial (x,z) }{ \partial (u,v) }$ have nonzero determinant at $q$.

In this case, we call $\varphi$ a parametrization of $S$ at $p$.