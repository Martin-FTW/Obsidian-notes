Book: [[Munkres Topology (MT)]]
# Theorem 29.1 (Characterization of locally compact Hausdorff spaces as the unique subspace of compact Hausdorff)
Let $X$ be a topological space.
Then $X$ is locally compact Hausdorff iff $\exists$ topological space $Y\supseteq X$ s.t.
1. $X$ is a subspace of $Y$
2. $Y\setminus X$ is a singleton
3. $Y$ is compact Hausdorff

The extension $Y$ is unique up to homeomorphism that restricts to identity on $X$, i.e.
- If another $Y'$ satisfy these conditions, then $\exists$ homeomorphism $\varphi:Y\to Y'$ s.t. $\varphi \vert_{X}=\id_{X}$.

Note that if $X$ is not compact, then the point $\infty\in Y\setminus X$ is a limit point of $X$, and $\cl_{Y}(X)=Y$.