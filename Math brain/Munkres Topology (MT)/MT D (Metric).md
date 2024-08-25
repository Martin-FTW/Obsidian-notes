Book: [[Munkres Topology (MT)]]
# Definition (Metric)
Let $X$ be a set.
A metric on $X$ is a function $d:X^{2}\to \mathbb{R}$ that satisfies:
- Positivity: $\forall x,y\in X:d(x,y)\geq 0$, "$=$" iff $x=y$
- Symmetric: $\forall x,y\in X:d(x,y)=d(y,x)$
- Triangle inequality: $\forall x,y,z\in X:d(x,z)\leq d(x,y)+d(y,z)$

In this case, we call $d(x,y)$ the distance between $x$ and $y$ in the metric $d$.
In addition, given $\epsilon>0$, the set $B_{d}(x,\epsilon)=\set{y\given d(x,y)<\epsilon}$ is called the $\epsilon$-ball centered at $x$.
