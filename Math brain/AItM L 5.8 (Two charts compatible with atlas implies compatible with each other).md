Book: [[Tu An Introduction to Manifolds (AItM)]]
# Lemma 5.8 (Two charts compatible with atlas implies compatible with each other)
Let $M$ be a locally Euclidean space.
Let $\mathfrak{U}=\set{(U_{\alpha},\phi_{\alpha})}$ be an atlas.
Let $(V,\psi),(W,\sigma)$ charts of $M$.
Suppose both charts are compatible with the atlas $\mathfrak{U}$.
Then $(V,\psi),(W,\sigma)$ are compatible.
#### Proof
Let $p\in V\cap W$.
Since $\mathfrak{U}$ is an atlas, $\exists \alpha$ s.t. $p\in U_{\alpha}$.
Now $p\in V\cap W\cap U_{\alpha}$.
Since $\sigma \circ \psi ^{-1}=(\sigma \circ \phi_{\alpha}^{-1})\circ(\phi_{\alpha}\circ \psi ^{-1})$ is $C^{\infty}$ on $\psi(V\cap W\cap U_{\alpha})$, in particular it is $C^{\infty}$ at $\psi(p)$.
It follows that $\sigma \circ \psi ^{-1}$ is $C^{\infty}$ on $\psi(V\cap W)$.
Similarly, $\psi \circ \sigma ^{-1}$ is $C^{\infty}$ on $\sigma(V\cap W)$.