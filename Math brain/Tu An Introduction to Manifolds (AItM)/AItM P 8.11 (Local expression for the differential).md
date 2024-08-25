Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 8.11 (Local expression for the differential)
Let $N,M$ be manifolds and $p\in N$.
Let $(U,x^{1},\dots,x^{n})$ be a chart about $p$ in $N$ and $(V,y^{1},\dots,y^{m})$ be a chart about $F(p)$ in $M$.
Let $\displaystyle \beta=\set*{\left.\left.\frac{ \partial }{ \partial x^{j} }\right\vert_{p}},\beta'=\set*{\frac{ \partial }{ \partial y^{i} }\right\vert_{F(p)}}$ be bases for $T_{p}N$ and $T_{F(p)}M$ respectively.
Then $\displaystyle [F_{*,p}]_{\beta}^{\beta'}=\left[ \frac{ \partial F^{i}}{ \partial x^{j} } \right]$ the Jacobian matrix
That is, $\displaystyle F_{*}\left( \left.\left.\frac{ \partial }{ \partial x^{j} }\right\vert_{p} \right)=\sum_{i=1}^{m}\frac{ \partial F^{i}}{ \partial x^{j} }(p)\frac{ \partial }{ \partial y^{i} }\right\vert_{F(p)}$ for $j\in\ii{1}{n}$.