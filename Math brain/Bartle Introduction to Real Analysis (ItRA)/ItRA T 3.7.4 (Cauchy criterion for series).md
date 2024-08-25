Book: [[Bartle Introduction to Real Analysis (ItRA)]]
# Theorem 3.7.4 (Cauchy criterion for series)
Let $(x_{n})$ be a sequence.
Then $\sum x_{n}$ converges $\iff$
- $\forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:\forall m,n\geq N$, if $m>n$ then $\displaystyle \abs*{\sum_{k=n+1}^{m}x_{k}}<\varepsilon$
- $\forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:\forall n\geq N,p\in \mathbb{Z}_{>0}:\displaystyle \abs*{\sum_{k=1}^{p}x_{n+k}}<\varepsilon$