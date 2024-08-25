Book: [[Tu An Introduction to Manifolds (AItM)]]
# Lemma 12.1 (Basis for tangent bundle)
Let $M$ be a manifold.
Let $\displaystyle \mathscr{B}=\bigcup_{\alpha}\set{A\given A\text{ open in }T(U_{\alpha}), U_{\alpha}\text{ is coordinate open set}}$, where $\alpha$ runs over all coordinate open sets in $M$.
Then
1. $\displaystyle TM=\cup \mathscr{B}=\bigcup_{A\in \mathscr{B}}A$
2. $\forall$ coordinate open sets $U,V$ in $M$, open sets $A$ in $TU$, $B$ in $TV$, $A\cap B$ is open in $T(U\cap V)$

Thus $\mathscr{B}$ is a basis for some topology on $TM$ by [[MT D (Basis)]]

#### Proof
Let $\set{(U_{\alpha},\phi_{\alpha})}$ be the maximal atlas for $M$.
Then $\displaystyle TM=\bigcup_{\alpha}TU_{\alpha}\subseteq \bigcup_{A\in \mathscr{B}}A\subseteq TM$. Hence $\mathscr{B}$ is a cover for $TM$.
Now let $U,V$ be coordinate open sets in $M$, $A$ be an open set in $TU$, and $B$ be an open set in $TV$.
Since $T(U\cap V)$ is a subspace of $TU$, we have $A'=A\cap T(U\cap V)$ is open in $T(U\cap V)$.
Similarly, $B'=B\cap T(U\cap V)$ is open in $T(U\cap V)$.
Since $A\cap B\subseteq TU\cap TV=T(U\cap V)$, we have $A\cap B=A\cap B\cap T(U\cap V)=A'\cap B'$ is open in $T(U\cap V)$.
