Book: [[Munkres Topology (MT)]]
# Theorem 26.5 (The image of a compact space under a continuous map is compact)
#### Proof
Let $f:X\to Y$ be continuous and $X$ be compact.
Let $\mathscr{A}$ be a covering of $f(X)$ by sets open in $Y$.
Then $\set{f^{-1}(A)}_{A\in \mathscr{A}}$ is an open covering of $X$ by continuity of $f$.
Since $X$ is compact, there is a subcover $\set{f^{-1}(A_{i})}_{i=1}^{n}$.
Now $\bigcup_{i}A_{i}\supset\bigcup_{i}f(f^{-1}(A_{i}))=f(\bigcup_{i}f^{-1}(A_{i}))\supset f(X)$.
Hence $\set{A_{i}}$ is a finite subcover, thus $f(X)$ is compact.