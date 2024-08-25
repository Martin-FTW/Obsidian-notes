Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Derivation induced from vector fields)
Let $U\subseteq \mathbb{R}^{n},X\in \mathfrak{X}(U),f\in C^{\infty}(U)$.
Define a new function $Xf:U\to \mathbb{R}$ by $(Xf)(p)=X_{p}f$ for any $p\in U$.
Writing $\displaystyle X=\sum a^{i}\dfrac{ \partial }{ \partial x^{i} }$, we get $(Xf)(p)=\displaystyle \sum a^{i}(p)\dfrac{ \partial f}{ \partial x^{i} }(p)$, thus $Xf=\displaystyle \sum a^{i}\dfrac{ \partial f}{ \partial x^{i} }$.
It follows that any $C^{\infty}$ vector field $X\in \mathfrak{X}(U)$ induces an $\mathbb{R}$-linear operator on $C^{\infty}(U)$ by $f\mapsto Xf$.
Note that this also means $X\in \mathfrak{X}(U)$ induces an derivation of the algebra $C^{\infty}(U)$, which is the map $\mathfrak{X}(U)\to \der(C^{\infty}(U)),X\mapsto(f\mapsto Xf)$.