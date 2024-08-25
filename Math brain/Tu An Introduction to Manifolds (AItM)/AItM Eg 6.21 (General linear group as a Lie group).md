Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 6.21 (General linear group as a Lie group)
Let $\GL(n,\mathbb{R})\subseteq \mathbb{R}^{n^{2}}$ denote the general linear group.
Since it is an open subset, it is a regular submanifold, thus a manifold.
Since $[AB]_{ij}=\sum a_{ik}b_{kj}$ is a polynomial, we have the product map $\mu:(\GL(n,\mathbb{R}))^{2}\to\GL(n,\mathbb{R})$ is smooth
By Cramer's rule, $\displaystyle [A^{-1}]_{ij}=\frac{(-1)^{i+j}M_{ji}}{\det A}=\frac{(-1)^{i+j}\det A(j|i)}{\det A}$ is again a polynomial of the entries, thus a smooth function.
Hence the inverse map $\iota:\GL(n,\mathbb{R})\to\GL(n,\mathbb{R})$ is smooth.
Hence $\GL(n,\mathbb{R})$ is a Lie group.