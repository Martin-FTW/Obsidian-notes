Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 14.4 (Smooth extension of a vector field)
Let $M$ be a manifold and $p\in M$.
Let $U$ be a nbhd of $p$ and $X$ be a smooth vector field on $U$.
Then $\exists$ smooth vector field $\tilde{X}$ on $M$ and $\exists$ nbhd $V\subseteq U$ of $p$ s.t. $\tilde{X}|_{V}=X|_{V}$ 
#### Proof
Choose a smooth bump function $\rho:M\to \mathbb{R}$ supported in $U$ with $\rho_{V}\equiv 1$ for some nbhd $V$ of $p$.
Let $\tilde{X}=\rho \cdot X\cdot \mathbb{1}_{U}$, that is $\tilde{X}(q)=\begin{cases}\rho(q)X_{q}& q\in U\\0& q\notin U\end{cases}$
Now follow [[AItM P 13.2 (Smooth extension of a function)]]
