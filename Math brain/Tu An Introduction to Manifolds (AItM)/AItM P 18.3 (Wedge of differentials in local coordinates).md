Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 18.3 (Wedge of differentials in local coordinates)
Let $M$ be manifold and $(U,\phi)=(U,x^{1},\dots,x^{n})$ be chart.
Let $f^{1},\dots,f^{k}\in C^{\infty}(U)$.
Then $\displaystyle df^{1}\wedge \cdots\wedge df^{k}=\sum_{(i_{1},\dots,i_{k})\in\mathcal{J}_{k,n}}\frac{ \partial (f^{1},\dots,f^{k}) }{ \partial (x^{i_{1}},\dots,x^{i_{k}}) }dx^{i_{1}}\wedge \cdots\wedge dx^{i_{k}}$
In particular, if $(\tilde{U},\tilde{\phi})=(\tilde{U},\tilde{x}^{1},\dots,\tilde{x}^{n})$ is another chart, then on $U\cap \tilde{U}$ we have the transition formula for $k$-forms: $\displaystyle d\tilde{x}^{J}=\sum_{I\in \mathcal{J}_{k,n}}\frac{ \partial (\tilde{x}^{j_{1}},\dots,\tilde{x}^{j_{k}}) }{ \partial (x^{i_{1}},\dots,x^{i_{k}}) }dx^{I}$
#### Proof
Locally on $U$, we have $\displaystyle df^{1}\wedge \cdots\wedge df^{k}=\sum_{J\in \mathcal{J}_{k,n}}c_{J}dx^{J}$.
Since $\displaystyle df^{i}\left( \frac{ \partial }{ \partial x^{j} } \right)=\frac{ \partial f^{i}}{ \partial x^{j} }$, we have
$\displaystyle \det\left[ \frac{ \partial f^{i}}{ \partial x^{i_{j}} } \right]$
$=(df^{1}\wedge \cdots\wedge df^{k})(\partial_{i_{1}},\dots,\partial_{i_{k}})$
$\displaystyle =\sum_{J\in \mathcal{J}_{k,n}}c_{J}dx^{J}(\partial_{I})$
$=\sum c_{J}\delta_{I}^{J}$
$=c_{I}$.