# Inverse function theorem
### Euclidean
Let $\Omega$ be an open set in $\mathbb{R}^n,a\in\Omega$
Let $f:\Omega\to\mathbb{R}^n$ be $C^1$.
Suppose the following equivalent statements:
- $Df(a)\in \mathcal{L}(\mathbb{R}^{n})$ is a linear isomorphism/invertible/bijective
- $Jf(a)$ is invertible/nonsingular
- $\det Jf(a)\neq 0$

Then the following equivalent statements hold:
- $f$ is a local diffeomorphism at $a$
- $\exists$ nbhd $U$ of $a$ s.t. $f|_{U}^{f(U)}:U\to f(U)$ is a $C^{1}$-diffeomorphism
- $\exists U\subseteq\Omega,V\subseteq\mathbb{R}^n:a\in U,f(a)\in V,\exists!g:V\to U:$
	1. $g=f^{-1}$, i.e. $g\circ f=\id_{U}$ and $f\circ g=\id_{V}$
	2. $g$ is $C^1$.
	3. $Dg|_y=(Df|_{g(y)})^{-1}$ for any $y\in V$