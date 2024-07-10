Book: [[Munkres Topology (MT)]]
# Theorem 17.9 (In T1 space, limit opint iff each neighbourhood intersects infinitely)
Let $X$ be a $T_{1}$ space, i.e. every finite set is closed.
Let $A\subset X$ and $x\in X$.
Then $x$ is a limit point of $A$ iff $\forall$ neighbourhood $U$ of $x$, $U\cap A$ is infinite.
#### Proof
$(\implies):$ Suppose $x$ is a limit point of $A$ but $\exists$ neighbourhood $U$ of $x$ s.t. $U\cap A$ is finite.
Then $U\cap(A\setminus \set{x})$ is finite. Write $\set{x_{i}}_{i=1}^{m}$ for this set.
Since $\set{x_{i}}_{i=1}^{m}$ is finite, it is closed, thus $X\setminus \set{x_{i}}$ is open.
Hence $U\cap(X\setminus \set{x_{i}})$ is open.
Since $x\notin \set{x_{i}}$, we have $x\in X\setminus \set{x_{i}}$, thus $x\in U\cap(X\setminus \set{x_{i}})$.
It follows that $U\cap(X\setminus \set{x_{i}})$ is an open neighbourhood of $x$.
Since $x$ is a limit point, we have $\exists a\in U\cap(X\setminus \set{x_{i}})\cap (A\setminus \set{x})$  
Now $a\in A\setminus \set{x}$ and $a\notin \set{x_{i}}\implies a\notin A\setminus \set{x}$. Contradiction.
$(\impliedby):$ Suppose every neighbourhood $U$ of $x$ has infinite intersection with $A$.
Then in particular it intersect $A$ at a point other than $x$.
Hence $x$ is a limit point of $A$.
