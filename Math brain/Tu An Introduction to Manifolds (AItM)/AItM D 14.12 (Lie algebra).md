Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 14.12 (Lie algebra)
Let $K$ be a field and $V$ be a vector space over $K$.
Let $[\cdot,\cdot]:V^{2}\to V$ be a binary operation called the *bracket*.
We call $V$ a *Lie algebra over $K$* if $\forall a,b\in K;X,Y,Z\in V:$
1. Bilinear: $\lie{aX+bY}{Z}=a\lie{X}{Z}+b\lie{Y}{Z}$ and $\lie{Z}{aX+bY}=a\lie{Z}{X}+b\lie{Z}{Y}$
2. Anticommutivity: $\lie{Y}{X}=-\lie{X}{Y}$
3. Jacobi identity: $\displaystyle\sum_{cyc}\lie{X}{\lie{Y}{Z}}=0$
Note that the bracket of a Lie algebra is not neccesarily associative