Book: [[Munkres Topology (MT)]]
# Theorem 23.4 (Adjoining limit points to connected subspaces is connected)
Let $A,B$ be subspaces of $X$.
Let $A$ be connected.
If $A\subset B\subset \overline{A}$, then $B$ is connected.
#### Proof
Suppose $C\cup D$ is a separation of $B$.
Then $A\subset C$ or $A\subset D$ by [[MT L 23.2 (Connected subspace in disconnected spaces)]].
WLOG, suppose $A\subset C$ and swap $C,D$ otherwise.
Now $\overline{A}\subset \overline{C}$, but $\overline{C}\cap D=\emptyset$, hence $\overline{A}\cap D=\emptyset$.
Since $B\subset \overline{A}$, we have $B\cap D=\emptyset$. Contradiction.