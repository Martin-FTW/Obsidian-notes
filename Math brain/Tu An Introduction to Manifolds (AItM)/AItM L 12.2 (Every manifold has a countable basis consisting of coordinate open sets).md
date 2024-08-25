Book: [[Tu An Introduction to Manifolds (AItM)]]
# Lemma 12.2 (Every manifold has a countable basis consisting of coordinate open sets)
#### Proof
Let $\set{(U_{\alpha},\phi_{\alpha})}$ be the maximal atlas on $M$ and $\mathscr{B}=\set{B_{i}}$be a countable basis for $M$.
Now for each $U_{\alpha}$ and each $p\in U_{\alpha}$, $\exists B_{p,\alpha}\in \mathscr{B}$ s.t. $p \in B_{p,\alpha}\subseteq U_{\alpha}$.
Thus by removing duplicates, $\set{B_{p,\alpha}}\subseteq \mathscr{B}$ is countable.
Now let $U$ be open in $M$ and $p\in U$.
Then $\exists U_{\alpha}$ s.t. $p\in U_{\alpha}\subseteq U$ by [[AItM Ex 5.4 (Existence of a coordinate neighbourhood)]]
Thus the corresponding $B_{p,\alpha}$ satisfies $p\in B_{p,\alpha}\subseteq U$
It follows that $\set{B_{p,\alpha}}$ is a countable basis for $M$.
