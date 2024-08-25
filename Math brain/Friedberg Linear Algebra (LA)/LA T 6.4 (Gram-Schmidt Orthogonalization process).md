Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 6.4 (Gram-Schmidt Orthogonalization process)
Let $V$ be an inner product space and $S=\set{w_{i}}_{i=1}^{n}$ be a linearly independent subset of $V$.
Define $S'=\set{v_{i}}_{i=1}^{n}$ by the following inductive process:
1. $v_{1}=w_{1}$
2. $\displaystyle v_{k}=w_{k}-\sum_{j=1}^{k-1}\frac{\innerp{w_{k}}{v_{j}}}{\norm{v_{j}}^{2}}v_{j}$ for all $k\in\ii{2}{n}$.

THen $S'$ is an orthogonal set of nonzero vectors sltl $\span S'=\span S$.