Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 17.10 (Commutation of pullback with differential)
Let $N,M$ be manifolds and $F:N\to M$ be smooth.
Then $\forall h\in C^{\infty}(M):F\pullback(dh)=d(F\pullback h)$.
#### Proof
Let $p\in N,X_{p}\in T_{p}N$.
Then 
$(F\pullback(dh))_{p}(X_{p})$
$=(F\pullback(dh)_{F(p)})(X_{p})$
$=(dh)_{F(p)}(F\pushforward[,p]X_{p})$
$=F\pushforward[,p](X_{p})(h)$
$=X_{p}(h\circ F)$
$=X_{p}(F\pullback h)$
$=d(F\pullback h)_{p}(X_{p})$