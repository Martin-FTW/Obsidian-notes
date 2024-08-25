Book: [[Munkres Topology (MT)]]
# Theorem 26.7 (FInite product of compact spaces is compact)
#### Proof
Let $X,Y$ be compact spaces and $\mathscr{A}$ be an open covering of $X\times Y$.
Given $x\in X$, we have $\set{x}\times Y\cong Y$ is compact, thus can be covered by finitely many elements $\set{A_{i}}_{i=1}^{m}\subset \mathscr{A}$.
Now $N_{x}=\bigcup_{i} A_{i}$ is an open set containing $\set{x}\times Y$.
By [[MT L 26.8 (The tube lemma)]], $N_{x}$ contains a tube $W_{x}\times Y$ about $\set{x}\times Y$.
Now $W_{x}\times Y$ is covered by the finite $\set{A_{i}}_{i=1}^{m}\subset \mathscr{A}$.
Hence $\set{W_{x}}_{x\in X}$ is an opencovering of $X$.
Since $X$ is compact, we have some finite subcover $\set{W_{i}}_{i=1}^{n}$.
Now $\bigcup_{i}(W_{i}\times Y)=X\times Y$.
Since each $W_{i}\times Y$ has a finite subcover from $\mathscr{A}$, the union of all these subcovers is a finite subcover of $X\times Y$ from $\mathscr{A}$.
Hence $X\times Y$ is compact.