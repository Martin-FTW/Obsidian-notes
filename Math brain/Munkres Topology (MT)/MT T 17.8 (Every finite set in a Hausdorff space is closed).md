Book: [[Munkres Topology (MT)]]
# Theorem 17.8 (Every finite set in a Hausdorff space is closed)
#### Proof
Since finite union of closed sets is closed, it suffices to show that every singleton is closed.
Let $x_{0}\in X$. Let $x\in X$ s.t. $x\neq x_{0}$.
Then there are neighbourhoods $U$ of $x_{0}$, $V$ of $x$ s.t. $U\cap V=\emptyset$.
Since $U\cap \set{x_{0}}=\emptyset$, we have $x\notin\cl \set{x_{0}}$ by [[MT T 17.5 (Closure characterization)]].
Hence $\cl \set{x_{0}}=\set{x_{0}}$, thus $\set{x_{0}}$ is closed.