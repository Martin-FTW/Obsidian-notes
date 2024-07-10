Book: [[Munkres Topology (MT)]]
# Theorem 17.4 (Closure in subspace)
Let $Y$ be a subspace of $X$ and $A\subset Y$.
Then $\cl_{Y} A=(\cl_{X}A)\cap Y$.
#### Proof
Since $\cl_{X}A$ is closed in $X$, we have $\cl_{X}A\cap Y$ is closed in $Y$ by [[MT T 17.2 (Closed in subspace)]].
Hence $\cl_{Y}A\subset \cl_{X}A\cap Y$.
Now sinec $\cl_{Y}A$ is closed in $Y$, $\exists C$ closed in $X$ s.t. $\cl_{Y}A=C\cap Y$ by [[MT T 17.2 (Closed in subspace)]].
Since $C$ is closed and contains $A$, we have $\cl_{X}A\subset C$.
Thus $\cl_{Y}A=C\cap Y\supset\cl_{X}A\cap Y$.