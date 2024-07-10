Book: [[Munkres Topology (MT)]]
# Theorem 17.6 (Closure is set with its limit points)
Let $A$ be a subset of the topological space $X$.
Let $A'$ be the set of all limit points of $A$.
Then $\bar{A}=A\cup A'$.
#### Proof
Let $x\in \bar{A}$. Then $x\in A$ or $x\notin A$.
If $x\in A$ then $x\in A\cup A'$.
If $x\notin A$ then every neighbourhood $U$ of $x$ intersects $A$ at some $a\in A$.
Since $x\notin A$, we have $x\neq a$, thus $x\in A'$ by definition.
It follows that $x\in A\cup A'$.
In any case, we get $\bar{A}\subset A\cup A'$.
Now let $x\in A\cup A'$.
If $x\in A$ then by $A\subset \bar{A}$ we have $x\in \bar{A}$.
If $x\in A'$ then every neighbourhood $U$ of $x$ intersects $A$ in a point different from $x$.
In particular, every neighbourhood of $x$ intersects $A$.
Thus $x\in \bar{A}$ by [[MT T 17.5 (Closure characterization)]]