Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 19.1 (Exterior derivative)
Let $M$ be a manifold.
Let $D:\Omega^*(M)\to \Omega^*(M)$ be an $\mathbb{R}$-linear map
We call $D$ an exterior derivative if
1. $D$ is an antiderivation of degree $1$, i.e. $\forall \omega\in \Omega^{k}(M),\uptau\in \Omega^{\ell}(M):$$D(\omega \wedge\uptau)=D\omega \wedge\uptau+(-1)^{k}\omega \wedge D\uptau\in \Omega^{k+\ell}(M)$
2. $D\circ D=0$
3. $\forall f\in C^{\infty}(M),X\in \mathfrak{X}(M):(Df)(X)=Xf$.

Note that 3. says that exterior derivatives agrees with the differential $df$ on $0$-forms, as $Df=df=\sum \frac{ \partial f}{ \partial x^{i} }dx^{i}$
