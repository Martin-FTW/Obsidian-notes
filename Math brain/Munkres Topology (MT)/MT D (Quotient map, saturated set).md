Book: [[Munkres Topology (MT)]]
# Definition (Quotient map, saturated set)
Let $X,Y$ be topological spaces.
Let $p:X\to Y$ be a surjective map.
We call $C\subset X$ saturated w.r.t. $p$ if
- $\forall y\in Y:$ if $p ^{-1}(\set{y})\cap C\neq \emptyset$ then $p ^{-1}(\set{y})\subset C$.

We call $p$ a quotient map if the following equivalent statements holds:
- $\forall U\subset Y:(U$ is open iff $p ^{-1}(U)$ is open$)$
- $p$ is continuous and $\forall$ saturated open $U\subset X:p(U)$ is open in $Y$

