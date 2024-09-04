Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 11.16 (Multiplication map of special linear group)
Let $\mu:\GL(n,\mathbb{R})\times\GL(n,\mathbb{R})\to \GL(n,\mathbb{R})$ be the multiplication map $\mu(A,B)=AB$.
Then $\mu$ is smooth as it is a polynomial of the coordinates $a_{ik},b_{kj}$.
Now since $\SL(n,\mathbb{R})\times\SL(n,\mathbb{R})$ is a regular submanifold of $\GL(n,\mathbb{R})\to\GL(n,\mathbb{R})$, we have the inclusion map $i:\SL(n,\mathbb{R})\times\SL(n,\mathbb{R})\to \GL(n,\mathbb{R})\times\GL(n,\mathbb{R})$ is smooth by [[AItM T 11.14 (A regular submanifold is an embedded submanifold by inclusion)]].
Hence $\mu \circ i:\SL(n,\mathbb{R})\times\SL(n,\mathbb{R})\to\GL(n,\mathbb{R})$ is smooth.
Now $\bar{\mu}:\SL(n,\mathbb{R})\times\SL(n,\mathbb{R})\to\SL(n,\mathbb{R})$ is smooth by [[AItM T 11.15 (Restricting the codomain of a smooth map to a regular submanifold preserve smoothness)]]