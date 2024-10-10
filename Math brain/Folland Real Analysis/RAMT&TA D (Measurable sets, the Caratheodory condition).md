Book: [[Folland Real Analysis Modern Techniques and Their Application (RAMT&TA)]]
# Definition (Measurable sets, the Caratheodory condition)
Let $X$ be a set and $\mu^*:\power(X)\to \clcl{0}{\infty}$
A set $A\subseteq X$ is called $\mu^*$-measurable of it satisfies the Caratheodory condition:
- $\forall E\subseteq X:\mu^*(E)=\mu^*(E\cap A)+\mu^*(E\cap A^\complement)$

The set of all $\mu^*$-measurable sets is denoted by $\mathcal{M}_{\mu^*}$.

Note that if $\mu^*$ is an outer measure, then by subadditivity, the Caratheodory condition is equivalent to
- $\forall E\subseteq X$ s.t. $\mu^*(E)<\infty$, $\mu^*(E)\geq \mu^*(E\cap A)+\mu^*(E\cap A^\complement)$