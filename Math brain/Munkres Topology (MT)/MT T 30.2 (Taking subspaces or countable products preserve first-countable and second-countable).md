Book: [[Munkres Topology (MT)]]
# Theorem 30.2 (Taking subspaces or countable products preserve first-countable and second-countable)
#### Proof\
Let $X$ be a topological space, $A$ be a subspace of $X$.
Suppose $X$ is second-countable. Then $\exists$ countable basis $\mathscr{B}$ for $X$.
Thus $\set{B\cap A\given B\in \mathscr{B}}$ is a countable basis for $A$.
Suppose $X$ is first-countable. Then $\forall x\in X$, $\exists$ local basis $\mathscr{B}_{x}$ at $x$.
Let $a\in A$ and take $\mathscr{B}_{a}'=\set{B\cap A\given B\in\mathscr{B}_{a}}$.
Then $\forall$ nbhd $U$ of $a$ in $A$, we have $U\subseteq A$.
Since $\mathscr{B}_{a}$ is a local basis at $a$, $\exists B\in \mathscr{B}_{a}$ s.t. $U\subseteq B$.
Now $U\subseteq B\cap A\in \mathscr{B}_{a}'$, hence $\mathscr{B}_{a}'$ is a local basis at $a$ for $A$.

Let $X_{i}$ be countably many topological spaces.
Suppose $X_{i}$ are second-countable. Then $\exists$ countable bases $\mathscr{B}_{i}$ for $X_{i}$.
Now $\set{\prod U_{i}\given \exists \set{i_{j}}_{j=1}^{n}:U_{i_{j}}\in \mathscr{B}_{i_{j}}\text{ and for }i\notin \set{i_{j}}_{j=1}^{n},U_{i}=X_{i}}$ is a countable basis for $\prod X_{i}$.
Suppose $X_{i}$ are first-countable.
Let $x=(x_{i})\in \prod X_{i}$. Then $\exists$ local basis $\mathscr{B}_{x_{i}}$ at $x_{i}$.
Now $\set{\prod U_{i}\given \exists \set{i_{j}}_{j=1}^{n}:U_{x_{i_{j}}}\in \mathscr{B}_{x_{i_{j}}}\text{ and for }i\notin\set{i_{j}}_{i=1}^{n},U_{i}=X_{i}}$ is a countable basis at $x$.