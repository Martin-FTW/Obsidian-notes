Book: [[Folland Real Analysis Modern Techniques and Their Application (RAMT&TA)]]
# Definition (Inner regularity, outer regularity, regular measure)
Let $X$ be a metric space.
Let $\mu:\mathcal{B}(X)\to \clcl{0}{\infty}$ be a Borel measure on $X$.
For $A\in \mathcal{B}(X)$, we call $\mu$
- inner regular on $A$ if $\mu(A)=\sup \set{\mu(K)\given K\subseteq A,K\text{ compact}}$
- outer regular on $A$ if $\mu(A)=\inf \set{\mu(U)\given A\subseteq U,U\text{ open}}$

We call $\mu$:
- inner regular if $\mu$ is inner regular on all borel sets $A\in \mathcal{B}(X)$
- outer regular if $\mu$ is outer regular on all borel sets $A\in \mathcal{B}(X)$
- regular if $\mu$ is both inner regular and outer regular