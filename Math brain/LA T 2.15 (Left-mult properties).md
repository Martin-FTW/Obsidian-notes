Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 2.15 (Left-mult properties)
Let $A$ be an $m\times n$ matrix in $F$.
Then $L_{A}:F^{n}\to F^{m}$ is linear.
Now let $B$ be an $m\times n$ matrix in $F$ and $\beta,\gamma$ standard ordered bases for $F^{n},F^{m}$.
Then
1. $[L_{A}]_{\beta}^{\gamma}=A$
2. $L_{A}=L_{B}$ iff $A=B$
3. $L_{A+B}=L_{A}+L_{B}$ and $L_{aA}=aL_{A}$ for all $a\in F$.
4. If $T:F^{n}\to F^{m}$ is linear, then $\exists!C\in M_{m\times n}(F):T=L_{C}$, then $C=[T]_{\beta}^{\gamma}$
5. If $E$ is an $n\times p$ matrix, then $L_{AE}=L_{A}L_{E}$
6. If $m=n$ then $L_{I_{n}}=I_{F^{n}}$.