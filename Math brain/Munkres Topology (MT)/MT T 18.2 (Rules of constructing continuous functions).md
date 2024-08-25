Book: [[Munkres Topology (MT)]]
# Theorem 18.2 (Rules of constructing continuous functions)
Let $X,Y,Z$ be topological spaces.
1. Let $f:X\to Y$ be a constant function. (i.e. $\exists y_{0}\in Y:\im f=\set{y_{0}}$)
   Then $f$ is continuous.
2. Let $A\subseteq X$ and the inclusion function $j:A\to X$. (i.e. $j(a)=a$)
   Then $j$ is continuous.
3. Let $f:X\to Y,g:Y\to Z$.
   Then $g\circ f:X\to Z$ is continuous
5. Let $A\subseteq X$ be a subspace and $f:X\to Y$ be continuous
   Then the restriction $f|_{A}:A\to Y$ is continuous.
6. Let $f:X\to Y$ be continuous
   Suppose $Y$ is a subspace of $Z$, or $Z$ is a subspace of $Y$.
   Then the expansion/restriction $f|_{X}^{Z}:X\to Z$ is continuous.
7. Let $f:X\to Y$ be a function.
   Suppose $\exists$ open cover $\set{U_{\alpha}}$ of $X$ s.t. $f|_{U_{\alpha}}$ is continuous $\forall \alpha$.
   Then $f$ is continuous.