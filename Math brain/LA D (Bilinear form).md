Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Bilinear form)
Let $V$ be a vector space over a field $F$.
Let $H:V^{2}\to F$ be a function.
We call $H$ a bilinear form on $V$ if $H(x_{0},\cdot),H(\cdot,y_{0})$ are linear $\forall x_{0},y_{0}\in V$.
In other words, the $\forall a\in F,x_{0},x_{1},x_{2},y_{0},y_{1},y_{2}\in V$, we have $H(ax_{1}+x_{2},y_{0})=aH(x_{1},y_{0})+H(x_{2},y_{0})$ and $H(x_{0},ay_{1}+y_{2})=aH(x_{0},y_{1})+H(x_{0},y_{2})$.

We denote by $\mathcal{B}(V)$ the set of all bilinear forms on $V$.