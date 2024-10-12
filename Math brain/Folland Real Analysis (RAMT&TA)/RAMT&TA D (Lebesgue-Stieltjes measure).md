Book: [[Folland Real Analysis (RAMT&TA)]]
# Definition (Lebesgue-Stieltjes measure)
Let $F:\mathbb{R}\to \mathbb{R}$ be increasing and right-continuous.
Then we have a unique Borel measure $\mu_{F}$ on $\mathbb{R}$ by [[RAMT&TA T 1.16 (Every increasing right-continuous function induces a unique Borel measure on reals, every Borel measure induces a distribution function)]]
Now we have the completion $\bar{\mu}_{F}$ of $\mu_{F}$ on a domain $\overline{\mathcal{B}(\mathbb{R})}$ containing $\mathcal{B}(\mathbb{R})$ by [[RAMT&TA T 1.9 (Every measure extends uniquely to a complete measure)]] 
We call this complete measure the Lebesgue-Stieltjes measure associated to $F$.
Denote by $\mu:\mathcal{M}_{\mu}\to \clcl{0}{\infty}$ the Lebesgue-Stieltjes measure associated to $F$.
Then for any $E\in \mathcal{M}_{\mu}$,
- $\begin{align}\mu(E)&=\inf \set*{\sum_{j=1}^{\infty}(F(b_{j})-F(a_{j}))\given E\subseteq \bigcup_{j=1}^{\infty}\opcl{a_{j}}{b_{j}}}\\&=\inf\set*{\sum_{j=1}^{\infty}\mu(\opcl{a_{j}}{b_{j}})\given E\subseteq \bigcup_{j=1}^{\infty}\opcl{a_{j}}{b_{j}}}\end{align}$