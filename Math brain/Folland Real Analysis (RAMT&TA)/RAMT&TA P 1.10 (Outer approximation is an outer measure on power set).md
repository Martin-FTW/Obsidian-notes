Book: [[Folland Real Analysis (RAMT&TA)]]
# Proposition 1.10 (Outer approximation is an outer measure on power set)
Let $X$ be a set.
Let $\mathcal{E}\subseteq \power(X)$ be a collection of subsets s.t. $\emptyset,X\in \mathcal{E}$.
Let $\rho:\mathcal{E}\to \clcl{0}{\infty}$ be s.t. $\rho(\emptyset)=0$.
Define $\mu^*:\power(X)\to \clcl{0}{\infty}$ by $\forall A\subseteq X:$ $\begin{align}\displaystyle\mu^*(A)&=\inf \set*{\sum_{j=1}^{\infty}\rho(E_{j})\given \exists(E_{j})\subseteq \mathcal{E}:A\subseteq\bigcup_{j=1}^{\infty}E_{j}}\\&=\inf \set*{\sum_{j=1}^{\infty}\rho(E_{j})\given (E_{j})\subseteq \mathcal{E}\text{ is a cover for }A}\end{align}$.
Then $\mu^*$ is an outer measure.