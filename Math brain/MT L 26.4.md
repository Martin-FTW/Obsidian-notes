Book: [[Munkres Topology (MT)]]
# Lemma 26.4
Let $Y$ be a compact subspace of the Hausdorff space $X$.
Let $x_{0}\in X\setminus Y$.
Then $\exists$ disjoint open sets $U,V$ of $X$ s.t. $x_{0}\in U$ and $Y\subset V$.
#### Proof
For each $y\in Y$, we have disjoint nbhd $U_{y}$ of $x_{0}$ and $V_{y}$ of $y$ by Hausdorff.
Now $\set{V_{y}}_{y\in Y}$ is an open covering of $Y$ by sets open in $X$.
Since $Y$ is compact, there is a finite subcover $\set{V_{y_{i}}}_{i=1}^{n}$.
Take $V\coloneqq \bigcup_{i}V_{y_{i}}$ and $U=\bigcap_{i}U_{y_{i}}$. 
Thus $x_{0}\in U$, $Y\subset V$ and $V$ is open.
Now $\forall z\in V:\exists i\in\ii{1}{n}:z\in V_{y_{i}}$, then $z\notin U_{y_{i}}$, thus $z\notin U$.
It follows that $U,V$ are disjoint.