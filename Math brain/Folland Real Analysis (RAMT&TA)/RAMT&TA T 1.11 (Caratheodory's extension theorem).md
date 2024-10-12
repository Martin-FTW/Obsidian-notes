Book: [[Folland Real Analysis (RAMT&TA)]]
# Theorem 1.11 (Caratheodory's extension theorem)
Let $X$ be a set
Let $\mu^*:\power(X)\to \clcl{0}{\infty}$ be a function s.t. $\mu^*(\emptyset)=0$
Let $\mathcal{M}_{\mu^*}$ be the set of $\mu^*$-measurable sets.
Then
1. We have
	- $\mathcal{M}_{\mu^*}$ is an algebra 
	- $\mu^*|_{\mathcal{M}_{\mu^*}}$ is finitely additive
2. $\forall$ disjoint $(E_{n})\subseteq \mathcal{M}_{\mu^*},\forall T\in \power(X):$
	- $\displaystyle \mu^*\left(  T\cap \bigcup_{i=1}^{n}E_{i} \right)=\sum_{i=1}^{n}\mu^*(T\cap E_{i})$
	- $\displaystyle \mu^*\left(  T\cap \bigcup_{i=1}^{\infty}E_{i} \right)=\sum_{i=1}^{\infty}\mu^*(T\cap E_{i})+\lim_{n} \mu^*\left( T\cap \bigcup_{j=n}^{\infty}E_{j} \right)$\
3. If $\mu^*$ is an outer measure, then 
	- $\mathcal{M}_{\mu^*}$ is a $\sigma$-algebra
	- $\mu^*|_{\mathcal{M}_{\mu^*}}$ is a complete measure.