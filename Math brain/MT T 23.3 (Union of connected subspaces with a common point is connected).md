Book: [[Munkres Topology (MT)]]
# Theorem 23.3 (Union of connected subspaces with a common point is connected)
#### Proof
Let $\set{A_{\alpha}}$ be a collection of connected subspaces of $X$.
Let $p\in \bigcap_{\alpha} A_{\alpha}$ and $Y=\bigcup_{\alpha}A_{\alpha}$.
Suppose $Y$ is disconnected. Then $\exists$ a separation $C\cup D=Y$.
Since $C\cap D=\emptyset$, we have $p\in C$ or $p\in D$.
WLOG, suppose $p\in C$ and swap $C,D$ otherwise.
For each $\alpha$, we have $A_{\alpha}\subset C$ or $A_{\alpha}\subset D$ by [[MT L 23.2 (Connected subspace in disconnected spaces)]].
Since $p\in C\cap A_{\alpha}$ for each $\alpha$, we must have $A_{\alpha}\subset C$ for all $\alpha$.
Then $D=\emptyset$. Contradiction.
It follows that $Y$ is connected.