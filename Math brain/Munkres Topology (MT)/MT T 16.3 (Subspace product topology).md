Book: [[Munkres Topology (MT)]]
# Theorem 16.3 (Subspace product topology)
Let $A$ be a subspace of $X$ and $B$ be a subspace of $Y$.
Then the product topology on $A\times B$ is equal to the subspace topology of $A\times B\subset X\times Y$.
#### Proof
Let $\mathscr{B}_{0},\mathscr{B}_{1}$ be the bases in the definition of product topology for $X\times Y$ and $A\times B$ respectively.
Let $\mathscr{B}=\set{C\cap(A\times B)\given C\in \mathscr{B}_{0}}$.
Then $\mathscr{B}$ is a basis for the subspace topology by [[MT L 16.1 (Basis for subspace topology)]].
Now
$$\begin{align}
\mathscr{B}&=\set{C\cap(A\times B)\given C\in \mathscr{B}_{0}} \\
&=\set{(U\times V)\cap(A\times B)\given U\subset X,V\subset Y\text{ open}} \\
&=\set{(U\cap A)\times(V\cap B)\given U\subset X, V\subset Y\text{ open}} \\
&=\set{U_{1}\times V_{1}\given U_{1}\subset A,V_{1}\subset  B\text{ open}} \\
&= \mathscr{B}_{1}
\end{align}$$
Thus the bases for the subspace topology and product topology are equal.
Hence the topologies are the same