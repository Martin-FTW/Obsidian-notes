Book: [[Munkres Topology (MT)]]
# Lemma 26.8 (The tube lemma)
Let $X,Y$ be topological spaces where $Y$ is compact.
Let $N$ be open in $X\times Y$ that contains $\set{x_{0}}\times Y$.
Then $\exists$ nbhd $W\subset X$ of $x_{0}$ s.t. $W\times Y\subset N$.
#### Proof
Note that $\set{U\times V\given \text{basis elements }U\times V\subset N}$ is an open cover of $\set{x_{0}}\times Y$.
Since $\set{x_{0}}\times Y\cong Y$ is compact, we have finite subcover $\set{U_{i}\times V_{i}}_{i=1}^{n}$.
WLOG, suppose each $U_{i}\times V_{i}$ intersects $\set{x_{0}}\times Y$ and remove it from the cover otherwise.
Then $W=\bigcap_{i}U_{i}$ is an open set in $X$ with $x_{0}\in W$.
Now let $x \times y\in W\times Y$. Then $\exists i\in\ii{1}{n}:x_{0}\times y\in U_{i}\times V_{i}$.
Since $x\in W=\bigcap_{i}U_{i}$, we have $x\in U_{i}$, thus $x \times y\in U_{i}\times V_{i}$.
It follows that $\set{ U_{i}\times V_{i}}_{i}$ covers $W\times Y$.
Hence $W$ is a nbhd of $x_{0}$ s.t. $W\times Y\subset N$.
