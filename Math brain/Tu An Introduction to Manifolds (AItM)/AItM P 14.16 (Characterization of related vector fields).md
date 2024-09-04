Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 14.16 (Characterization of related vector fields)
Let $N,M$ be manifolds and $F:N\to M$ be smooth.
Let $X$ be a vector field on $N$ and $\bar{X}$ be a vector field on $M$.
Then $X$ is $F$-related to $\bar{X}$ iff $\forall g\in C^{\infty}(M):X(g\circ F)=(\bar{X}g)\circ F$.
#### Proof
$(\implies):$ Let $g\in C^{\infty}(M)$.
Then for all $p\in N$, we have $((\bar{X} g)\circ F)(p)=\bar{X}g(F(p))=\bar{X}_{F(p)}g=F_{*,p}(X_{p})g=X_{p}(g\circ F)=X(g\circ F)(p)$.
Hence $X(g\circ F)=(\bar{X}g)\circ F$.
$(\impliedby):$ as above