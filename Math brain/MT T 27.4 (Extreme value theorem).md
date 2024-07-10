Book: [[Munkres Topology (MT)]]
# Theorem 27.4 (Extreme value theorem)
Let $f:X\to Y$ be continuous and $Y$ is an ordered set with order topology.
Suppose $X$ is compact.
Then $\exists c,d \in X:\forall x\in X:f(c)\leq f(x)\leq f(d)$.
That is $\min f(X),\max f(X)$ exists in $Y$.
#### Proof
Since $f$ is continuous and $X$ is compact, we have $A\coloneqq f(X)$ is compact.
Suppose $A$ has no largest element.
Then $\set{(-\infty,a)}_{a\in A}$ is an open covering of $A$.
Since $A$ is compact, a finite subcover $\set{(-\infty,a_{i})}_{i=1}^{n}$ exists.
Now $\max \set{a_{i}}\in A$ but is not in the cover. Contradiction.  
Thus $A$ has a largest element.
Similarly, $A$ has a least element