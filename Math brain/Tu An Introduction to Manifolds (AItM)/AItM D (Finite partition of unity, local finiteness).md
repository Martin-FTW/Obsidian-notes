Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Finite partition of unity, local finiteness)
Let $S$ be a topological space and $\set{U_{i}}_{i\in I}$ be a finite open cover of $M$.
Let $\set{\rho _{i}}_{i\in I}\subseteq C^{\infty}(S)$ be a collection of nonnegative smooth functions, i.e. $\rho _{i}\geq 0$ for all $i\in I$.
We call $\set{\rho _{i}}_{i\in I}$ a smooth partition of unity subordinate to $\set{U_{i}}_{i\in I}$ if each $\rho _{i}$ is supported in $U_{i}$ and their pointwise sum is $1$ everywhere, i.e.
1. $\supp\rho _{i}\subseteq U_{i}$ for all $i\in I$
2. $\sum \rho _{i}=1$

If $I$ were finite, the sum may not make sense, thus we define local finiteness below:
Let $\set{A_{\alpha}}$ be a collection of subsets of $S$.
We call $\set{ A_{\alpha}}$ locally finite if every point has a neighbourhood that intersects only finitely many of its sets, i.e. 
- $\forall q\in S:\exists$ nbhd $U$ of $x$ s.t. $\set{A_{\alpha}\given U\cap A_{\alpha}\neq \emptyset}$ is finite

In particular, each point $q\in S$ is contained in only finitely many $A_{\alpha}$'s