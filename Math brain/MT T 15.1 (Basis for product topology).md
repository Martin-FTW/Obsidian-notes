Book: [[Munkres Topology (MT)]]
# Theorem 15.1 (Basis for product topology)
Let $\mathscr{B}$ be a basis for the topology of $X$ and $\mathscr{C}$ be a basis for the topology of $Y$.
Then the collection $\mathscr{D}=\set{B\times C\given B\in \mathscr{B},C\in \mathscr{C}}$ is a basis for the product topology of $X\times Y$.
#### Proof 
Let $\Omega$ be an open set in $X\times Y$. Let $x \times y\in \Omega$.
Then $\exists$ basis element $U\times V$ s.t. $x\times y\in U\times V\subset \Omega$.
Since $\mathscr{B},\mathscr{C}$ are bases and $U,V$ are open, $\exists B\in \mathscr{B},C\in \mathscr{C}$ s.t. $x\in B\subset U,y\in C\subset V$.
Now $x \times y\in B\times C\subset U\times V\subset \Omega$.
Hence $\mathscr{D}$ is a basis for $X\times Y$.