Book: [[Munkres Topology (MT)]]
# Theorem 16.4 (Order topology is subspace topology for convex )
Let $X$ be an ordered set with order topology.
Let $Y\subset X$ be convex.
Then the order topology on $Y$ is the same as the subspace topology on $Y$ inherited from $X$.
#### Proof
Denote $(a,+\infty)_{X}$ a ray in $X$ and $(a,+\infty)_{Y}$ the ray in $Y$.

Let $(a,+\infty)_{X}$ be a ray.
- If $a\in Y$ then $(a,+\infty)_{X}\cap Y=(a,+\infty)_{Y}$
- If $a\notin Y$ then $(a,+\infty)_{X}\cap Y=Y$ or $\emptyset$ by the convexity of $Y$.

In any case, $(a,+\infty)_{X}\cap Y$ is open in the order topology.
Similarly, $(-\infty,a)_{X}\cap Y$ is open in the order topology
Since $\set{(-\infty ,a)_{X},(a,+\infty)_{X}\given a\in X}$ forms a subbasis for the order topology of $X$, we have $\set{(-\infty ,a)_{X}\cap Y,(a,+\infty)_{X}\cap Y\given a\in X}$ is a subbasis for the subspace topology of $Y$.
Now since all elements in the subbasis is open in the order topology of $Y$, the order topology is finer than the subspace topology.

Now any open ray $(a,+\infty)_{Y},(-\infty,a)_{Y}$ is the intersection of its $X$-counterpart and $Y$, thus is open in the subspace topology of $Y$.
Since $\set{(-\infty,a)_{Y},(a,\infty)_{Y}\given a\in Y}$ is a subbasis for the order topology on $Y$, and all its elements is open in the subspace topology, the subspace topology is finer than the order topology.