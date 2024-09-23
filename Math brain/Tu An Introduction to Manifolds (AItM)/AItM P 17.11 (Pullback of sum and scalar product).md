Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 17.11 (Pullback of sum and scalar product)
Let $N,M$ be manifolds.
Let $F:N \to M$ be smooth.
Then $\forall \omega,\uptau\in \Omega^{1}(M),g\in C^{\infty}(M)$,
1. $F\pullback(\omega+\uptau)=F\pullback \omega+F\pullback\uptau$
2. $F\pullback(g\omega)=(F\pullback g)(F\pullback \omega)$.
#### Proof
Let $p\in N,X_{p}\in T_{p}N$.
$(F\pullback(\omega+\uptau))_{p}(X_{p})$
$=(\omega+\uptau)_{F(p)}(F\pushforward X_{p})$
$=\omega_{F(p)}(F\pushforward X_{p})+\uptau_{F(p)}(F\pushforward X_{p})$
$=(F\pullback \omega+F\pullback\uptau)_{p}(X_{p})$
