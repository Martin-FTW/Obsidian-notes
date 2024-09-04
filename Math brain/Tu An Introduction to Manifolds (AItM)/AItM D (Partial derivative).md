Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Partial derivative)
Let $M$ be a manifold of dimension $n$.
Let $(U,\phi)$ be a chart on $M$.
Let $f:M\to \mathbb{R}^{n}$ be $C^{\infty}$.
Denote by $r^{1},\dots,r^{n}$ the standard coordinates on $\mathbb{R}^{n}$, and $x^{i}=r^{i}\circ \phi$ the components of $\phi$.
Let $p\in U$.
Then we define the partial derivative of $f$ with respect to $x^{i}$ at $p$ by:
$$\left.\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}f\coloneqq\frac{ \partial f}{ \partial x^{i} }(p)\coloneqq\frac{ \partial (f\circ \phi ^{-1})}{ \partial r^{i} }(\phi(p))=\frac{ \partial  }{ \partial r^{i} }\right\vert_{\phi(p)}(f\circ \phi ^{-1})$$
Since $\displaystyle \frac{ \partial f}{ \partial x^{i} }(p)=\frac{ \partial f}{ \partial x^{i} }(\phi ^{-1}(\phi(p)))=\frac{ \partial (f\circ \phi ^{-1})}{ \partial x^{i} }(\phi(p))$, we have $\displaystyle\frac{ \partial f}{ \partial x^{i} }\circ \phi ^{-1}=\frac{ \partial (f\circ \phi ^{-1}) }{ \partial r^{i} }$ as functions on $\phi(U)$.
Note that $\displaystyle \frac{ \partial f}{ \partial x^{i} }$ is $C^{\infty}$ since its pullback by $\phi ^{-1}$ is $C^{\infty}$ by above.
