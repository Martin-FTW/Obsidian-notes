Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 8.19 (Differential of left multiplication in general linear group)
Let $g\in\GL(n,\mathbb{R})$ and $\ell_{g}:\GL(n,\mathbb{R})\to\GL(n,\mathbb{R})$ be the left multiplication by $g$.
Then since $\GL(n,\mathbb{R})$ is an open subset of $\mathbb{R}^{n\times n}$, we have $T_{g}\GL(n,\mathbb{R})\simeq T_{g}\mathbb{R}^{n\times n}\simeq \mathbb{R}^{n\times n}$
The identification is $\displaystyle\sum a_{ij}\frac{ \partial }{ \partial x_{ij} }$
Show that $(\ell_{g})\pushforward[,I]:T_{I}\GL(n,\mathbb{R})\to T_{g}\GL(n,\mathbb{R})$, under this identification, is $\ell_{g}:\mathbb{R}^{n\times n}\to \mathbb{R}^{n\times n}$ itself.
#### Proof\
Let $X\in T_{I}\GL(n,\mathbb{R})\simeq \mathbb{R}^{n\times n}$.
By [[AItM P 8.16 (Existence of a curve with a given initial vector)]], we can choose some curve $c(t)$ in $\GL(n,\mathbb{R})$ s.t. $c(0)=I,c'(0)=X$.
Now by [[AItM P 8.18 (Computing differential using curves)]], we have $(\ell_{g})\pushforward[,I](X)=(\ell_{g}\circ c)'(0)=\left.\frac{d}{dt}\right\vert_{0}gc(t)=g\left.\frac{d}{dt}\right\vert_{0}c(t)=gc'(0)=gX$ by [[AItM P 8.15 (Velocity of a curve in local coordinates)]]