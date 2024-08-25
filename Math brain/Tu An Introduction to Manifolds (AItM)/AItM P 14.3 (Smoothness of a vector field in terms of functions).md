Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 14.3 (Smoothness of a vector field in terms of functions)
Let $M$ be a manifold and $X$ be a vector field.
Then $X$ is smooth iff $\forall f\in C^{\infty}(M):Xf$ is smooth on $M$.
#### Proof
$(\implies):$ Suppose $X$ is smooth and let $f\in C^{\infty}(M)$.
Thus for any chart $(U,\phi)=(U,x^{1},\dots,x^{n})$ on $M$, the coefficients $a^{i}$ of $\displaystyle X=\sum a^{i}\frac{ \partial }{ \partial x^{i} }$ are smooth by [[AItM P 14.2 (Smoothness of a vector field in terms of coefficients)]].
Hence $\displaystyle Xf=\sum a^{i}\frac{ \partial f }{ \partial x^{i} }$ is smooth on $U$.
Since $M$ can be covered by charts, $Xf$ is smooth on $M$.
$(\impliedby):$ Let $(U,\phi)=(U,x^{1},\dots,x^{n})$ be any chart on $M$.
Suppose $\displaystyle X=\sum a^{i}\frac{ \partial }{ \partial x^{i} }$ on $U$ and $p\in U$. By [[AItM P 13.2 (Smooth extension of a function)]], each $x^{k}$ can be extended to a smooth $\tilde{x}^{k}$ on $M$ s.t. $\tilde{x}^{k}=x^{k}$ in a nbhd $V$ of $p$ in $U$. (This is required as the $f$ in hypothesis is on $M$ not on $U$)
Now on $V$, we have $\displaystyle X\tilde{x}^{k}=\left( \sum a^{i}\frac{ \partial }{ \partial x^{i} } \right)\tilde{x}^{k}=\left( \sum a^{i}\frac{ \partial }{ \partial x^{i} } \right)x^{k}=a^{k}$.
By hypothesis, $a^{k}$ is smooth on $V$, in particular smooth at $p$.
Hence $a^{k}$ is mooth on $U$.
By [[AItM P 14.2 (Smoothness of a vector field in terms of coefficients)]], $X$ is smooth.