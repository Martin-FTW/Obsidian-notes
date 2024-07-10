Book: [[Munkres Topology (MT)]]
# Definition (Limit point)
Let $X$ be a topological space.
Let $x \in X$ and $A\subset X$.
We call $x$ a limit point of $A$ if these equivalent statements hold
- every neighbourhood of $x$ intersects $A$ in some point other than $x$.
- every neighbourhood of $x$ intersects $A\setminus \set{x}$
- $x\in \cl(A\setminus \set{x})$
- for any open $U$, if $x\in U$ then $\exists a\in U\cap A$ s.t. $a\neq x$.