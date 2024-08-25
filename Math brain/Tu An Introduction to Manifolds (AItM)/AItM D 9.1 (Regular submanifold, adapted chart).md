Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 9.1 (Regular submanifold, adapted chart)
Let $N$ be a manifold of dimension $n$ and $S$ be a subspace of $N$.
Let $\mathfrak{N}$ be the maximal atlas of $N$.
We call $S$ a regular submanifold of dimension $k$ if
- $\forall p\in S: \exists$ chart $(U,\phi)=(U,x^{1},\dots,x^{n})\in \mathfrak{N}$ about $p$ s.t. 
	- $n-k$ coordinate functions vanishes on $U\cap S$, i.e. $x^{j}|_{U\cap S}\equiv 0$ 

By renumbering the vanishing coordinate functions, we can assume $x^{k+1},\dots,x^{n}$ vanishes, thus $\phi|_{U\cap S}=(x^{1},\dots,x^{k},0,\dots,0)$.
In this case, we define $\phi_{S}=(x^{1},\dots,x^{k}):U\cap S\to \mathbb{R}^{k}$ and call $(U,\phi)$ an adapted chart relative to $S$.
Note that $(U\cap S,\phi_{S})$ is a chart for $S$.
Unless otherwise specified, submanifold always means regular submanifold.