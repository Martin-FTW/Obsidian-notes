Book: [[Munkres Topology (MT)]]
# Theorem 18.4 (Maps into products)
Let $A,X,Y$ be topological spaces.
Let $f:A\to X\times Y$ be given by $f(a)=(f_{1}(a),f_{2}(a))$.
Then $f$ is continuous iff $f_{1},f_{2}$ are continuous.
#### Proof
$(\implies):$ Suppose $f$ is continuous.
Then $f_{1}=\pi_{1}\circ f$ and $f_{2}=\pi_{2}\circ f$ are continuous since $\pi_{1},\pi_{2},f$ are continuous.
$(\impliedby):$ Suppose $f_{1},f_{2}$ are continuous.
Note that $\mathscr{B}=\set{U\times V\given U\subset X,V\subset Y\text{ open}}$ is a basis for $X\times Y$.
Now $\forall U\times V\in \mathscr{B}$, $f^{-1}(U\times V)=f_{1}^{-1}(U)\cap f_{2}^{-1}(V)$ is open since $f_{1},f_{2}$ are continuous and $U,V$ are open.
Thus $f^{-1}(U\times V)$ is open.
It follows that $f$ is continuous.