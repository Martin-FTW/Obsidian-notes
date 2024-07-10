Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 2.18 (Inverse matrix representation)
Let $V,W$ be finite-dimensional vector spaces with ordered bases $\beta,\gamma$.
Let $T:V\to W$ be linear.
Then $T$ is invertible iff $[T]_{\beta}^{\gamma}$ is invertible.
Furthermore, $[T^{-1}]_{\gamma}^{\beta}=([T]_{\beta}^{\gamma})^{-1}$
## Lemma
Let $U:V\to W$ be linear and invertible.
Then $V$ is finite-dimensional iff $W$ is finite-dimension.
In this case, we have $\dim V=\dim W$.
## Corollary 1
If $V=W,\beta=\gamma$, then $T$ is invertible iff $[T]_{\beta}$ is invertible, in this case $[T^{-1}]{\beta}=([T]_{\beta})^{-1}$
## Corollary 2
Let $A$ be an $n\times n$ matrix. Then $A$ is invertible iff $L_{A}$ is invertible. 
Furthermore $L_{A}^{-1}=L_{A^{-1}}$.