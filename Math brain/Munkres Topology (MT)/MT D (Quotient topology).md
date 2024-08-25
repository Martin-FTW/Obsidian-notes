Book: [[Munkres Topology (MT)]]
# Definition (Quotient topology)
Let $X$ be a topological space and $A$ be a set.
Let $p:X\to A$ be a surjective function.
Then $\exists!$ topology $\mathscr{T}$ on $A$ s.t. $p$ is a quotient map on $\mathscr{T}$.
We call this the quotient topology induced by $p$.

The topology is obtained by $\mathscr{T}=\set{U\subset A\given p ^{-1}(U)\text{ open in }X}$.

Given an equivalence relation $\sim$ on $X$, we can take $A=X/{\sim}$ and the projection map $p=\pi:X\to X/{\sim}$.
In this case, the quotient topology is defined as $\mathscr{T}=\set{U\subseteq X/{\sim}\given\pi ^{-1}(U)\text{ is open}}$