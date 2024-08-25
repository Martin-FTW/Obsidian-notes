Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 6.24 (Jacobian of transition map)
Let $M$ be a manifold.
Let $(U,\phi)=(U,x^{1},\dots,x^{n})$ and $(V,\psi)=(V,y^{1},\dots,y^{n})$ be overlapping charts for $M$.
The transition map $\psi \circ \phi ^{-1}:\phi(U\cap V)\to \psi(U\cap V)$ has Jacobian matrix $\displaystyle J(\psi \circ \phi ^{-1})\vert_{\phi(p)}=\left[ \frac{ \partial y^{i} }{ \partial x^{j} }(p) \right]$
#### Proof
$\displaystyle \frac{ \partial (\psi \circ \phi ^{-1})^{i} }{ \partial r^{j} }=\frac{ \partial (r^{i}\circ \psi \circ \phi ^{-1}) }{ \partial r^{j} }(\phi(p))=\frac{ \partial (y^{i}\circ \phi ^{-1}) }{ \partial x^{j} }(\phi(p))=\frac{ \partial y^{i} }{ \partial x^{j} }(p)$