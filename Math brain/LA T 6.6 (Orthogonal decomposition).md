Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 6.6 (Orthogonal decomposition)
Let $W$ be a finite-dimensional subspace of an inner product space $V$.
Let $y\in V$.
Then $\exists! u\in W,z\in W^{\perp}$ s.t. $y=u+z$.
Furthermore, if $\set{v_{i}}_{i=1}^{k}$ is an orthonormal basis for $W$, then
$$u=\sum_{i=1}^{k}\innerp{y}{v_{i}{}}v_{i}$$
## Corollary
$u$ is the closest vector to $y$ in $W$, i.e. $\forall x\in W:\norm{y-x}\geq \norm{y-u}$, and equality holds iff $x=u$.