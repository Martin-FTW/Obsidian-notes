Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Orientable)
Let $S$ be a regular surface.
We call $S$ orientable if 
- $\exists$ parametrizations $\varphi_{\alpha}:U_{\alpha}\to S$ s.t. $\forall p\in \varphi_{\alpha_{1}}(U_{\alpha_{1}})\cap \varphi_{\alpha_{2}}(U_{\alpha_{2}})$,
	- the change of coordinates has positive Jacobian at $p$, i.e. $\det J(\varphi_{\alpha_{2}}^{-1}\circ \varphi_{\alpha_{1}})(p)=\det \dfrac{ \partial (u,v) }{ \partial (\eta,\xi) }>0$.

In this case, we call $\set{\varphi_{\alpha}}$ an orientation of $S$ and $S$ oriented.
Otherweise, we call $S$ nonorientable