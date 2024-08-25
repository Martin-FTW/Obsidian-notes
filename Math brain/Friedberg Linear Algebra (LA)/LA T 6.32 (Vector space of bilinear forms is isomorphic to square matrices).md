Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 6.32 (Vector space of bilinear forms is isomorphic to square matrices)
Let $V$ be an $n$-dimensional vector space over a field $F$.
Let $\beta$ be an ordered basis for $V$.
Then $\psi_{\beta}:\mathcal{B}(V)\to \mathcal{M}_{n}(F)$ is an isomorphism.
## Corollary 1
$\dim \mathcal{B}(V)=n^{2}$
## Corollary 2
$\forall H\in \mathcal{B}(V),A\in \mathcal{M}_{n}(F):[A=\psi_{\beta}(H)\iff \forall x,y\in V:H(x,y)=\phi_{\beta}(x)\transpose A\phi_{\beta}(y)]$.
## Corollary 3
Let $\beta'$ be the standard ordered basis for $F^{n}$.
Then $\forall H\in \mathcal{B}(F^{n}):\exists!A\in \mathcal{M}_{n}(F):\forall x,y\in F^{n}:H(x,y)=x\transpose Ay$.
Namely, we have $A=\psi_{\beta}(H)$.