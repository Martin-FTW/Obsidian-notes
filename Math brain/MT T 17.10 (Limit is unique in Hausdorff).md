Book: [[Munkres Topology (MT)]]
# Theorem 17.10 (Limit is unique in Hausdorff)
Let $X$ be a Hausdorff space and $(x_{n})$ be a sequence in $X$.
Then $(x_{n})$ converges to at most one point of $X$.
#### Proof
Suppose $(x_{n})$ converge to $x\in X$.
Let $y\neq x$. Then $\exists$ disjoint neighbourhoods $U$ of $x$ and $V$ of $y$.
Now $\exists N\in \mathbb{Z}_{>0}$ s.t. $\forall n\geq N$, $x_{n}\in U$.
It follows that $\forall N'\in \mathbb{Z}_{>0}$, $x_{\max \set{N,N'}}\notin V$.
Hence $x_{n}$ cannot converge to $y$.