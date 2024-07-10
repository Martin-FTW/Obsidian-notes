Book: [[Friedberg Linear Algebra (LA)]]
# Theorem 6.18 (Characterizations for unitary, orthogonal)
Let $T$ be a linear operator on a finite-dimensional inner product space $V$.
Then TFAE:
1. $\norm{T(x)}=\norm{x}$ for all $x\in V$
2. $TT^{*}=I=T^{*}T$
3. $\innerp{T(x)}{T(y)}{}=\innerp{x}{y}{}$ for all $x,y\in V$
4. If $\beta$ is an orthonormal basis for $V$, then $T(\beta)$ is an orthonormal basis for $V$
5. $\exists$ orthonormal basis $\beta$ for $V$ s.t. $T(\beta)$ is an orthonormal basis for $V$

Thus unitary/orthogonal implies normal.
## Lemma
Let $U$ be a self-adjoint operator on $V$.
If $\forall x\in V:\innerp{x}{U(x)}{}=0$, then $U=T_{0}$
## Corollary 1
Suppose $V$ is a finite-dimensional real inner product space.
Then TFAE:
1. $V$ has an orthonormal basis of eigenvectors of $T$ with corresponding eigenvalues of absolute value $1$
2. $T$ is self-adjoint and orthogonal
## Corollary 2
Suppose $V$ is a finite-dimensional complex inner product space.
Then TFAE:
1. $V$ has an orthonormal basis of eigenvectors of $T$ with corresponding eigenvalues of absolute value $1$
2. $T$ is unitary
