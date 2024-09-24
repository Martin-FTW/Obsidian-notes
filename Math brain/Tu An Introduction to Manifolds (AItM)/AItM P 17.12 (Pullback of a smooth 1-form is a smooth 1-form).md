Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 17.12 (Pullback of a smooth 1-form is a smooth 1-form)
Let $N,M$ be manifolds.
Let $F:N\to M$ be smooth and $\omega\in \Omega^{1}(M)$ be a smooth $1$-form on $M$.
Then $F\pullback \omega\in \Omega^{1}(N)$ is a smooth $1$-form on $N$.
That is, we have $F\pullback:\Omega^{1}(M)\to \Omega^{1}(N)$.
#### Proof
Let $p\in N$, and $(V,\psi)=(V,x^{1},\dots,x^{n})$ be a chart in $M$ about $F(p)$.
Since $F$ is continuous, $\exists$ chart $(U,\phi)=(U,x^{1},\dots,x^{n})$ about $p$ in $N$ s.t. $F(U)\subseteq V$.
Now on $V$, we have $\exists a_{i}\in C^{\infty}(V)$ s.t. $\omega=\sum a_{i}dy^{i}$.
Thus on $U$ we have 
$F\pullback \omega$
$=\sum(F\pullback a_{i})F\pullback(dy^{i})$
$=\sum (F\pullback a_{i})dF\pullback y^{i}$
$=\sum(a_{i}\circ F)\cdot d(y^{i}\circ F)$
$\displaystyle =\sum(a_{i}\circ F)\cdot \frac{ \partial F^{i} }{ \partial x^{j} }dx^{j}$ by [[AItM Ep (Local expression of 1-forms)]]

Now all $(a_{i}\circ F)\frac{ \partial F^{i}}{ \partial x^{j} }$ are smooth, thus $F\pullback \omega$ is smooth by [[AItM L 17.5 (1-form is locally smooth iff all the coefficient functions are smooth)]] 