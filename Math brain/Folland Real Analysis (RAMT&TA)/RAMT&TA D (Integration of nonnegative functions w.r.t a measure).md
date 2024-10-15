Book: [[Folland Real Analysis (RAMT&TA)]]
# Definition (Integration of nonnegative functions w.r.t a measure)
Let $(X,\mathcal{M},\mu)$ be a measure space.
Denote $L^{+}=\set{f:X\to \clcl{0}{\infty}\given f\text{ is measurable}}$.
Let $f\in L^{+}$.
Define $\displaystyle \int f\d \mu=\sup \set*{\int \phi \d\mu\given 0\leq \phi \leq f,\phi \text{ simple}}$ to be the integral of $f$ w.r.t $\mu$.
Note that $\forall f,g\in L^{+}c\in \clop{0}{\infty}$, we have 
1. If $f\leq g$ then $\int f \leq \int g$
2. $\int cf=c\int f$.