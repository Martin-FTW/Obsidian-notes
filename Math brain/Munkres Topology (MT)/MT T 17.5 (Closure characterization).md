Book: [[Munkres Topology (MT)]]
# Theorem 17.5 (Closure characterization)
Let $A$ be a subset of the topological space $X$.
Then $x\in \bar{A}$ iff every open set $U$ containing $x$ intersects $A$.
Further suppose $\mathscr{B}$ is a basis for the topology of $X$.
Then $x\in \bar{A}$ iff every basis element $B$ containing $x$ intersects $A$.
#### Proof
$(\implies):$ Suppose $x\in \bar{A}$ but $\exists$ oepn $U$ containing $x$ but $U\cap A=\emptyset$.
Then $A\subset X\setminus U$ and $X\setminus U$ is closed.
Thus $x\in \bar{A}\subset X\setminus U$.
Hence $x\in X\setminus U$. Contradiction.
$(\impliedby):$ Suppose every open set containing $x$ intersects $A$.
Let $C$ be a closed set containing $A$.
If $x\notin C$ then $x\in X\setminus C$. We also have $X \setminus C$ is open.
Hence $X\setminus C$ intersects $A$, but $A\subset C$ means $X \setminus C$ does not intersect $A$.
Contradiction.
It follows that $x\in C$.
Hence $x\in \bar{A}$ by definition.

Alternatively, if $x\notin \bar{A}$ then $U=X\setminus \bar{A}$ is open and contains $x$, thus intersect $A$, which is a contradiction.