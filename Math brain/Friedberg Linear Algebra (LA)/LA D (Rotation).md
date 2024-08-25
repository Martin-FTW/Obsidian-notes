Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Rotation)
Let $V$ be a finite-dimensional real inner product space.
Let $T$ be a linear operator on $T$.
We call $T$ a rotation if $T=\id_{V}$ or $\exists$ 
1. subspace $W\subseteq V$ with $\dim W=2$
2. orthonormal basis $\beta=\set{x_{1},x_{2}}$ for $W$
3. $\theta\in \mathbb{R}$

such that $\forall y\in W^{\perp}:T(y)=y$  and $$\begin{bmatrix}T(x_{1})\\T(x_{2})\end{bmatrix}=\begin{bmatrix}\cos \theta&\sin \theta\\-\sin \theta&\cos \theta\end{bmatrix}\begin{bmatrix}x_{1}\\x_{2}\end{bmatrix}$$
In this case, we call 
- $T$ a rotation of $W$ about $W^{\perp}$
- $W^{\perp}$ the axis of rotation
