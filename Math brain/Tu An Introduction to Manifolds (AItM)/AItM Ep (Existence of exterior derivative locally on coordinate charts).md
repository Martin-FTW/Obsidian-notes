Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exposition (Existence of exterior derivative locally on coordinate charts)
Let $M$ be a manifold and $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart on $M$.
Let $\omega$ be a $k$-form on $U$.
Then we have the unique linear comibnation $\omega=\sum a_{I}dx^{I}$, where $a_{I}\in C^{\infty}(U)$.
Now if $D$ is an exterior derivative on $U$, then we have
$D\omega=\sum(Da_{I})\wedge dx^{I}+\sum a_{I}Dx^{I}$
$=\sum (Da_{I})\wedge dx^{I}$
$\displaystyle =\sum_{i,j}\frac{ \partial a_{I} }{ \partial x^{j} }dx^{j}\wedge dx^{I}$
Thus if $D$ exists on $U$, then we must have $D\omega\displaystyle =\sum_{i,j}\frac{ \partial a_{I} }{ \partial x^{j} }dx^{j}\wedge dx^{I}$.
Conversely, define $d_{U}$ by $d_{U}\omega\displaystyle =\sum_{i,j}\frac{ \partial a_{I} }{ \partial x^{j} }dx^{j}\wedge dx^{I}$.
Then $d_{U}$ is the unique exterior derivative on $(U,\phi)$ similar to [[AItM P 4.7 (Properties of exterior derivative)]]