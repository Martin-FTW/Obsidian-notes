Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 13.2 (Smooth extension of a function)
Let $M$ be a manifold, $p\in M$, $U$ be a nbhd of $p$.
Let $f\in C^{\infty}(U)$.
Then $\exists \tilde{f}\in C^{\infty}(M)$ s.t. $\exists$ nbhd $V\subseteq U$ of $p$ s.t. $\tilde{f}|_{V}=f|_{V}$
#### Proof
Let $\rho:M\to \mathbb{R}$ be a smooth bump function supported in $U$ that is identically $1$ in some nbhd $V$ of $p$.
Let $\tilde{f}=\rho \cdot f\cdot\mathbb{1}_{U}$, i.e. $\tilde{f}(q)=\begin{cases}\rho(q)f(q)&\text{for }q\in U\\0&\text{for }q\notin U\end{cases}$
Now $\tilde{f}$ is smooth on $U$ as a product of two smooth functions.
For any $q\notin U$, we have $q\notin \supp \rho$.
Since $\supp \rho$ is closed, $\exists$ nbhd of $q$ disjoint from $\supp\rho$, thus $\tilde{f}\equiv 0$ on that nbhd.
Hence $\tilde{f}$ is smooth and $\tilde{f}=1\cdot f\cdot 1=f$ on $V$.