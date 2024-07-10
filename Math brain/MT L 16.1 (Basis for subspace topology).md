Book: [[Munkres Topology (MT)]]
# Lemma 16.1 (Basis for subspace topology)
Let $\mathscr{B}$ be a basis for the topology of $X$.
Then $\mathscr{B}_{Y}=\set{B\cap Y\given B\in \mathscr{B}}$ is a basis for the subspace topology on $Y$.
#### Proof
Let $U\cap Y$ be an open set in $Y$ and $x\in U\cap Y$.
Since $\mathscr{B}$ is a basis and $U$ is open in $X$, $\exists B\in \mathscr{B}$ s.t. $x\in B\subset U$.
Now since $x\in Y$, we have $x \in B\cap Y\subset U\cap Y$.
Hence $\mathscr{B}_Y$ is a basis for the subspace topology.