Book: [[Munkres Topology (MT)]]
# Theorem 24.3 (Intermediate value theorem)
Let $X$ be a connected space and $Y$ be an ordered set in order topology.
Let $f:X\to Y$ be a continuous map.
Let $a,b\in X,r\in Y$ s.t. $r\in(f(a),f(b))\cup(f(b),f(a))$.
Then $\exists c\in X:r=f(c)$.
#### Proof
Let $A=f(X)\cap(-\infty,r),B=f(X)\cap(r,+\infty)$.
Then $A\cap B=\emptyset$ and both are nonempty as they each contain one of $f(a),f(b)$.
Suppose no $c\in X$ exists s.t. $r=f(c)$.
Then $A\cup B=f(X)$, which is a separation of $f(X)$.
But $f(X)$ is connected by [[MT T 23.5 (Continuous map preserve connectedness)]]. Contradiction.