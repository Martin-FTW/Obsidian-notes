Book: [[Folland Real Analysis (RAMT&TA)]]
# Definition (Outer measure)
Let $X$ be a nonempty set.
Let $\mu ^*:\power(X)\to \clcl{0}{\infty}$ be a function
We call $\mu ^*$ an outer measure on $X$ if
1. $\mu ^*(\emptyset)=0$
2. Monotonicity: $\forall A,B\in \power(X):A\subseteq B\implies \mu^*(A)\leq \mu^*(B)$
3. Countable subadditivity: $\displaystyle \forall\set{A_{j}}_{j=1}^{\infty}\subseteq \power(X):\mu^*\left( \bigcup_{j=1}^{\infty}A_{j} \right)\leq \sum_{j=1}^{\infty}\mu^*(A_{j})$, 