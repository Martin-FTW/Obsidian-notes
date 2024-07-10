Book: [[Munkres Topology (MT)]]
# Theorem 26.9 (Compact iff every collection with FIP has nonempty intersection)
Let $X$ be a topological space.
Then $X$ is compact iff
- $\forall$ collection $\mathscr{C}$ of closed sets in $X$ with FIP, $\cap \mathscr{C}\coloneqq\displaystyle \bigcap_{C\in \mathscr{C}}C\neq \emptyset$.
## Lemma
Given a collection $\mathscr{A}$ of subsets of $X$, let $\mathscr{C}=\set{X\setminus A}_{A\in \mathscr{A}}$.
Then
1. $\mathscr{A}$ is a collection of open sets iff $\mathscr{C}$ is a collection of closed sets
2. $\mathscr{A}$ covers $X$ if $\cap \mathscr{C}=\emptyset$
3. The finite subcollection $\set{A_{i}}_{i=1}^{n}\subset \mathscr{A}$ covers $X$ iff the subcollection $\set{C_{i}}\subset \mathscr{C}$ given by $C_{i}=X\setminus A_{i}$ satisfies $\bigcap_{i}C_{i}=\emptyset$.
#### Proof
The second and third statement in lemma follows from $X\setminus \bigcup A_{\alpha}=\bigcap(X\setminus A_{\alpha})$.

Now $X$ is compact
$\iff\forall$ collection $\mathscr{A}$ of open sets, if $\mathscr{A}$ covers $X$ then $\exists$ finite subcollection of $\mathscr{A}$ that covers $X$
$\iff \forall$ collection $\mathscr{A}$ of open sets, if no finite subcollection of $\mathscr{A}$ covers $X$ then $\mathscr{A}$ does not cover $X$ (Contrapositive)
$\iff \forall$ collection $\mathscr{C}$ of closed sets, if no finite subcollections of $\set{X\setminus C}_{C\in \mathscr{C}}$ covers $X$ then $\set{X\setminus C}_{C\in\mathscr{C}}$ does not cover $X$ (by 1)
$\iff \forall$ collection $\mathscr{C}$ of closed sets, if no finite subcollection of $\mathscr{C}$ has empty intersection then $\set{X\setminus C}_{C\in \mathscr{C}}$ does not cover $X$ (by 2)
$\iff \forall$ collection $\mathscr{C}$ of closed sets, if no finite subcollection of $\mathscr{C}$ has empty intersection then $\cap\mathscr{C}\neq\emptyset$ (by 3)
$\iff \forall$ collection $\mathscr{C}$ of closed sets, if $\mathscr{C}$ has FIP then $\cap \mathscr{C}\neq \emptyset$ (by definition)