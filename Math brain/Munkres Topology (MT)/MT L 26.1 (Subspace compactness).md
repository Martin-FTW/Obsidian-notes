Book: [[Munkres Topology (MT)]]
# Lemma 26.1 (Subspace compactness)
Let $Y$ be a subspace of $X$.
Then $Y$ is compact iff every covering of $Y$ by open sets in $X$ has a finite subcover of $Y$.
#### Proof
$(\implies):$
Let $\mathscr{A}=\set{A_{\alpha}}$ be a covering of $Y$ by sets open in $X$.
Then $\set{A_{\alpha}\cap Y}_{\alpha\in J}$ is a open covering of $Y$.
Thus there is a finite subcover $\set{A_{\alpha_{i}}\cap Y}_{i=1}^{n}$ for $Y$.
Hence $\set{A_{\alpha_{i}}}$ is a finite subcover of $Y$ by open sets on $X$.
$(\impliedby):$
Let $\mathscr{A'}=\set{A_{\alpha}'}$ be an open covering of $Y$.
For each $\alpha$, choose an open subset $A_{\alpha}$ in $X$ s.t. $A_{\alpha}'=A_{\alpha}\cap Y$.
Then $\set{A_{\alpha}}$ is a covering of $Y$ be sets open in $X$.
Thus there is a subcover $\set{A_{\alpha_{i}}}$.
Hence $\set{A_{\alpha_{i}}'}$ is a subcover of $\mathscr{A}'$.