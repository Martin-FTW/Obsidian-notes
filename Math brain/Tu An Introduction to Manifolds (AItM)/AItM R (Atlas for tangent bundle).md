Book: [[Tu An Introduction to Manifolds (AItM)]]
# Remark (Atlas for tangent bundle)
Let $M$ be a manifold and $\set{(U_{\alpha},\phi_{\alpha})}$ be a smooth atlas for $M$.
Then $\set{(TU_{\alpha},\tilde{\phi}_{\alpha})}$ is a smooth atlas for $TM$.
#### Proof
Since $TM=\bigcup_{\alpha}TU_{\alpha}$, it is automatically a covering.
It remains to check any two charts $(TU_{\alpha},\tilde{\phi}_{\alpha}),(TU_{\beta},\tilde{\phi}_{\beta})$ are compatible
Write $U_{\alpha \beta}=U_{\alpha}\cap U_{\beta},\phi_{\alpha}=(x^{1},\dots,x^{n}),\phi_{\beta}=(y^{1},\dots,y^{n})$.
Then $\tilde{\phi}_{\beta}\circ \tilde{\phi}_{\alpha}^{-1}:\phi_{\alpha}(U_{\alpha \beta})\times \mathbb{R}^{n}\to \phi_{\beta}(U_{\alpha \beta}\times \mathbb{R}^{n})$ is given by $\displaystyle \tilde{\phi}_{\beta}\circ \tilde{\phi}_{\alpha}^{-1}(\phi_{\alpha}(p),a^{1},\dots,a^{n})=\tilde{\phi}_{\beta}\left( p,\sum_{j}a^{j}\left.\frac{ \partial }{ \partial x^{j} }\right\vert_{p} \right)=(\phi_{\beta}(p),b^{1},\dots,b^{n})$, where $\displaystyle b^{i}=\sum_{j}a^{j}\frac{ \partial y^{i} }{ \partial x^{j} }(p)$ by [[AItM P 8.10 (Transition matrix for coordinate vectors)]]
Now by [[AItM Eg 6.24 (Jacobian of transition map)]] we have $\displaystyle b^{i}=\sum_{j}a^{j}\frac{ \partial (\phi_{\beta}\circ \phi_{\alpha}^{-1})^{i} }{ \partial r^{j} }(\phi_{\alpha}(p))$
Since $\phi_{\beta}\circ \phi_{\alpha}^{-1}$ is smooth, we have $\tilde{\phi}_{\beta}\circ \tilde{\phi}_{\alpha}^{-1}$ is smooth.
Hence $\tilde{\phi}_{\alpha},\tilde{\phi}_{\beta}$ are compatible.
Thus $\set{(TU_{\alpha},\tilde{\phi}_{\alpha})}$ is a smooth atlas.