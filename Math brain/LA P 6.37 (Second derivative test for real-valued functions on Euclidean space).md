Book: [[Friedberg Linear Algebra (LA)]]
# Proposition 6.37 (Second derivative test for real-valued functions on Euclidean space)
Let $f:\mathbb{R}^{n}\to \mathbb{R}$ be a $C^{3}$ function.
Let $p=(p_{1},\dots,p_{n})\in \mathbb{R}^{n}$ be a critical point of $f$.
Denote by $Hf(p)=\left[ \frac{ \partial^{2} f }{ \partial x_{i}\partial x_{j} } \right]_{n\times n}$ the Hessian matrix of $f$ at $p$.
Then:
1. If all eigenvalues of $Hf(p)$ are positive, then $f$ has local min at $p$
2. If all eigenvalues of $Hf(p)$ are negative, then $f$ has local max at $p$
3. If both positive and negative eigenvalues exists, then $f$ has a saddle point at $p$, which is not a local extremum
4. If $\rank Hf(p)<n$ and $Hf(p)$ does not have both positive and negative eigenvalues, then the second derivative test is inconclusive
