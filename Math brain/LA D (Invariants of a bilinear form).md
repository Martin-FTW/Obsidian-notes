Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Invariants of a bilinear form)
Let $V$ be an $n$-dimensional vector space over $\mathbb{R}$.
Let $H$ be a symmetric bilinear form.
Let $\beta$ be a basis for $V$.
Let $D$ be a diagonal matrix representation of $H$, i.e. $\psi_{\beta'}(H)$ where $\beta'$ is an ordered basis s.t. $\psi_{\beta'}(H)$ is diagonal.
Define $\set{i_{k}}_{i=1}^{p}=\set{i\given d_{i}>0},\set{j_{k}}_{k=1}^{q}=\set{j\given d_{j}<0}$, where $D=\diag(d_{1},\dots,d_{n})$.
We call:
- $\psi_{\beta}(H)$ the rank of $H$
- $p$ the index of $H$
- $p-q$ the signature of $H$.
- the above $3$ values the invariants of $H$.

Note that the invariants are all invariant w.r.t. matrix representations, as:
- the rank is invariant by the change of coordinates matrix being invertible
- the index and signature is invariant by [[LA T 6.38 (Sylvester's Law of Intertia)]].