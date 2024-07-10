Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 6.25 (Spectral theorem)
Let $T$ be a linear operator on a finite-dimensional inner product space $V$ of a field $F$.
Suppose $\lambda_{1},\dots,\lambda_{k}$ are the distinct eigenvalues of $T$.
Suppose $T$ is normal if $F=\mathbb{C}$, or self-adjoint if $F=\mathbb{R}$.
Let $T_{i}$ be the orthogonal projection of $V$ on $E_{\lambda_{i}}$.
Then
1. $V=\oplus E_{\lambda_{i}}$
2. $E_{\lambda_{i}}^{\perp}=\oplus_{j\neq i}E_{\lambda_{j}}$ for all $i\in\ii{1}{k}$
3. $T_{i}T_{j}=\delta_{ij}T_{i}$ for $i,j\in\ii{1}{k}$
4. $I=\sum T_{i}$ (Resolution of identity)
5. $T=\sum \lambda_{i}T_{i}$ (Spectral decomposition)

## Corollary 1
If $F=\mathbb{C}$, then $T$ is normal iff $T^{*}=g(T)$ for some $g\in \mathbb{C}[x]$.
## Corollary 2
If $F=\mathbb{C}$, then $T$ is unitary iff $T$ is normal and $\abs{\lambda}=1$ for each eigenvalue $\lambda$ of $T$.
## Corollary 3
If $F=\mathbb{C}$ and $T$ is normal, then $T$ is self-adjoint iff every eigenvalue of $T$ is real
## Corollary 4
$\forall j\in\ii{1}{k}:\exists g\in \mathbb{C}[x]:T_{j}=g(T)$.