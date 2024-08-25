Book: [[Munkres Topology (MT)]]
# Definition (Continuous)
Let $X,Y$ be topological spaces.
Let $f:X\to Y$ be a function.
We call $f$ continuous at $x\in X$ if
- $\forall$ nbhd $V$ of $f(x)$, $\exists$ nbhd $U$ of $x$ s.t. $f(U)\subset V$.

We call $f$ continuous if 
- $\forall$ open $V$ in $Y$, $f^{-1}(V)$ is open in $X$

If $\mathscr{B}$ is a basis for $X$, it suffices to show that $f^{-1}(B)$ is open for any $B\in \mathscr{B}$ for $f$ to be continuous.
If $\mathcal{S}$ is a subbasis for $X$, it suffices to show that $f^{-1}(S)$ is open for any $S\in \mathcal{S}$ for $f$ to be continuous.