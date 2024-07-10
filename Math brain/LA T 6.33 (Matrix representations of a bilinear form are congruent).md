Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 6.33 (Matrix representations of a bilinear form are congruent)
Let $V$ be a $n$-dimensional vector space over a field $F$.
Let $\beta=\set{v_{i}}_{i=1}^{n},\gamma=\set{w_{i}}_{i=1}^{n}$ be ordered bases of $V$.
Let $Q=[I_{V}]_{\gamma}^{\beta}$ be the change of coordinates matrix from $\gamma$-coords to $\beta$-coords.
Then $\forall H\in \mathcal{B}(V):\psi_{\gamma}(H)=Q\transpose\psi_{\beta}(H)Q$.
In particular, $\psi_{\gamma}(H)$ is congruent to $\psi_{\beta}(H)$.
## Corollary
$\forall B\in \mathcal{M}_{n}(F)$ congruent to $\psi_{\beta}(H)$, $\exists$ ordered basis $\beta'$ for $V$ s.t. $\psi_{\beta'}(H)=B$.
In this case, $\forall$ invertible $Q'\in \mathcal{M}_{n}(F):B=Q'\transpose\psi_{\beta}(H)Q'$.