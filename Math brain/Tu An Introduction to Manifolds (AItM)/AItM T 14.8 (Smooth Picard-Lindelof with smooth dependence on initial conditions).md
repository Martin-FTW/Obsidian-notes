Book: [[Tu An Introduction to Manifolds (AItM)]]
# Theorem 14.8 (Smooth Picard-Lindelof with smooth dependence on initial conditions)
Let $V\subseteq \mathbb{R}^{n}$ be open, $p_{0}\in V$, and $f:V\to \mathbb{R}^{n}$ be smooth.
Then $\exists \varepsilon>0$, nbhd $W\subseteq V$ of $p_{0}$ and a smooth function $y:\opop{-\varepsilon}{\varepsilon}\times W\to V$ s.t. $\forall (t,q)\in \opop{-\varepsilon}{\varepsilon},q\in W:\begin{cases}\displaystyle \frac{\partial y}{\partial t}(t,q)=f(y(t,q))\\y(0,q)=q\end{cases}$ 
## Corollary
Let $M$ be a manifold, $X$ be a vector field on $M$.
Let $U$ be a chart and $p\in U$.
Then $\exists \varepsilon>0$, nbhd $W$ of $p$ in $U$, and a smooth map $F:\opop{-\varepsilon}{\varepsilon}\times W\to U$ s.t. $\forall q\in W:F_{t}(q)$ is an integral curve of $X$ starting at $q$.