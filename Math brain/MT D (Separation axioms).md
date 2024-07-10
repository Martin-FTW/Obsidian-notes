Book: [[Munkres Topology (MT)]]
# Definition (Regular space, normal space, T3, T4)
Let $X$ be a topological space. 
1. We call $X$ a $T_{0}$ space if (unused)
2. We call $X$ a $T_{1}$ space if every singleton is closed, i.e.
	- $\forall x\in X:\set{x}$ is closed.
3. We call $X$ a $T_{2}$ space if every pair of distinct points are separated by nbhds, i.e.
	- $\forall$ distinct $x,y\in X$, $\exists$ nbhds $U\ni x,V\ni y$ s.t. $U\cap V=\emptyset$
4. We call $X$ regular if every pair of disjoint point oand closed set are separated by nbhds, i.e.
	- $\forall$ closed $B\subseteq X$, $\forall x\in X\setminus B$, $\exists$ open sets $U\ni x,V\supseteq B$ s.t. $U\cap V=\emptyset$
5. We call $X$ normal if every pair of disjoint closed sets are separated by nbhds, i.e.
	- $\forall$ closed $A,B\subseteq X$, $\exists$ open sets $U\supseteq A,V\supseteq B$ s.t. $U\cap V=\emptyset$
6. We call $X$ a $T_{3}$ space if $X$ is $T_{0}$ and regular (also called regular Hausdorff)
7. We call $X$ a $T_{4}$ space if $X$ is $T_{0}$ and normal (also called normal Hausdorff)