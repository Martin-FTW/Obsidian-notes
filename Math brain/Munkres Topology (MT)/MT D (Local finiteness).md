Book: [[Munkres Topology (MT)]]
# Definition (Local finiteness)
Let $X$ be a topological space.
Let $\mathscr{A}\subseteq \power(X)$ be a collection of subsets of $X$.
We say that $\mathscr{A}$ is locally finite in $X$ if 
- $\forall x\in X:\exists$ nbhd $U$ of $x$ s.t. $U$ intersects only finitely many elements of $\mathscr{A}$.

Now let $\set{A_{\alpha}}_{\alpha\in J}$ be an indexed family of subsets of $X$.
We call $\set{A_{\alpha}}$ a locally finite indexed family in $X$ if 
- $\forall x\in X:\exists$ nbhd $U$ of $x$ s.t. $U$ intersects $A_{\alpha}$ for finitely many $\alpha\in J$.

Note the equivalence:
1. $\set{A_{\alpha}}_{\alpha\in J}$ is a locally finite indexed family
2. $\set{A_{\alpha}}$ is locally finite and $\forall$ nonempty $A\in \power(X)$, $A=A_{\alpha}$ for at most finitely many $\alpha\in J$.