Book: [[Munkres Topology (MT)]]
# Theorem 23.5 (Continuous map preserve connectedness)
Let $f:X\to Y$ be a continuous function.
If $X$ is connected, then $f(X)$ is connected.
#### Proof
Note that $f:X\to f(X)$ is continuous by [[MT T 18.2 (Rules of constructing continuous functions)]].
Suppose $f(X)$ is disconnected.
Then $\exists$ clopen set $B$ that is nonempty and not $f(X)$.
Now $f^{-1}(B)$ is clopen as well.
Since $X$ is connected, we have $f^{-1}(B)=X$ or $f^{-1}(B)=\emptyset$.
Since $B\subset f(X)$, $f^{-1}(B)=\emptyset$ is impossible.
But now $f(X)=f(f^{-1}(B))=B$ by surjectivity. Contradiction.