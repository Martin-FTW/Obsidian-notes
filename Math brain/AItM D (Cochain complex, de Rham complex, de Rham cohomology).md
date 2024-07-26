Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Cochain complex, de Rham complex, de Rham cohomology)
Let $\set{V^{k}}_{k=0}^{\infty}$ be a collection of vector spaces.
Let $d_{k}:V^{k}\to V^{k+1}$
We call $\set{V^{k}}$ a cochain complex if $d_{k+1}\circ d_{k}=0$.
Now let $U\subseteq \mathbb{R}^{n}$ be open.
Then the exterior derivative $d:\Omega ^*(U)\to \Omega ^*(U)$ makes $\set{\Omega^{k}(U)}$ into a cochain complex.
We call this the de Rham complex of $U$.
The quotient vector space $\displaystyle H^{k}(U)=\frac{\set{\omega\in \Omega ^{k}(U)\given \omega \text{ is closed}}}{\set{\omega\in \Omega ^{k}(U)\given \omega \text{ is exact}}}$ is called the $k$-th de Rham cohomology on $U$.