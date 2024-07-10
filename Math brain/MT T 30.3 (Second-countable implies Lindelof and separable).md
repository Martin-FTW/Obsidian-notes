Book: [[Munkres Topology (MT)]]
# Theorem 30.3 (Second countable implies Lindelof and separable)
Let $X$ be topological space.
Suppose $X$ is second-countable.
Then:
1. $X$ is a Lindelöf space, i.e. $\forall$ open covering of $X$, $\exists$ countable subcover
2. $X$ is a separable space, i.e. $\exists$ countable dense $A\subseteq X$.

Each converse holds if $X$ is metrizable.
#### Proof
Let $\set{B_{n}}$ be a countable basis for $X$.
Let $\mathscr{A}$ be an open covering of $X$.
Denote $\set{n_{k}}=\set{n\given \exists A_{n}\in \mathscr{A}:B_{n}\subseteq A_{n}}$. Then $\set{A_{n_{k}}}$ is countable.
Now let $x\in X$. Then $\exists A\in \mathscr{A}$ s.t. $x\in A$.
Since $A$ is open, $\exists$ basis element $B_{m}$ s.t. $x\in B_{m}\subseteq A$.
Hence $m\in \set{n_{k}}$, thus $x\in B_{m}\subseteq A_{m}$.
It follows that $\set{A_{n_{k}}}$ is a countable subcover.
Now $\forall n$, take some $x_{n}\in B_{n}$.
Claim: $\set{x_{n}}$ is dense in $X$.
Proof: Let $x\in X$. 
Then for any basis element $B_{n}\ni x$, we have $x_{n}\in B_{n}$, thus $B_{n}\cap \set{x_{n}}\neq \emptyset$.
It follows that $x\in \cl_{X}\set{x_{n}}$.