Book: [[Munkres Topology (MT)]]
# Theorem 27.3 (In euclidean, compact iff closed and bounded)
Let $A$ be a subspace of $\mathbb{R}^{n}$.
Then $A$ is compact iff $A$ is closed and bounded in the euclidean metric $d$ or the square metric $\rho$.
#### Proof
Since $\rho(x,y)\leq d(x,y)\leq \sqrt{ n }\rho(x,y)$, we have $A$ is bounded under $d$ iff $A$ is bounded under $\rho$, thus it suffices to consider only $\rho$.

$(\implies):$ Suppose $A$ is compact.
Since $\mathbb{R}^{n}$ Hausdorff, we have $A$ is closed by [[MT T 26.3 (Every compact subspace of a Hausdorff space is closed)]].
Now consider the open covering $\set{B_{\rho}(0,m)}_{m\in \mathbb{Z}_{>0}}$.
Since $A$ is compact, there is a finite subcover.
Thus $\exists M\in \mathbb{Z}_{>0}:A\subset B_{\rho}(0,M)$.
Now $\forall x,y\in A:\rho(x,y)\leq \rho(x,0)+\rho(0,y)\leq 2M$.
Hence $A$ is bounded
$(\impliedby):$ Suppose $A$ is closed and bounded under $\rho$.
Then $\exists N>0:\forall x,y\in A:\rho(x,y)\leq N$.
Pick any $x_{0}\in A$ and let $b=\rho(x_{0},0)$.
Then $\forall x\in A:\rho(x,0)\leq \rho(x,x_{0})+\rho(x_{0},0)\leq N+b$.
Now $A\subset[-N-b,N+b]^{n}$, which is compact.
Since $A$ is closed, it is compact by [[MT T 26.2 (Every closed subspace of a compact space is compact)]].
