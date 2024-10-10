Book: [[Folland Real Analysis Modern Techniques and Their Application (RAMT&TA)]]
# Proposition 1.15 (Every increasing right-continuous function induces a premeasure on the algebra of h-intervals)
Let $F:\mathbb{R}\to \mathbb{R}$ be an increasing and right-continuous function.
Let $\mathcal{E}=\set{\opcl{a}{b}\given a<b}$ be the elementary family of h-intervals.
Let $\mathcal{A}$ be the algebra induced by $\mathcal{E}$ by [[RAMT&TA P 1.7 (Collection of finite disjoint unions of an elementary family is an algebra)]]
Now define $\mu_{0}:\mathcal{A}\to \clcl{0}{\infty}$ by $\mu_{0}(\emptyset)=0$ and $\displaystyle\mu_{0}\left( \bigsqcup_{j=1}^{n}\opcl{a_{j}}{b_{j}} \right)=\sum_{j=1}^{n}(F(b_{j})-F(a_{j}))$ for all $\displaystyle \bigsqcup_{j=1}^{n}\opcl{a_{j}}{b_{j}}\in \mathcal{A}$.
Then $\mu_{0}$ is a premeasure on $\mathcal{A}$.