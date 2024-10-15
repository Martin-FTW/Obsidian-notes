Book: [[Folland Real Analysis (RAMT&TA)]]
# Definition (Integral of nonnegative simple function w.r.t. a measure)
Let $(X,\mathcal{M},\mu)$ be a measure space.
Denote $L^{+}=\set{f:X\to \clcl{0}{\infty}\given f\text{ is measurable}}$.
Now let $\phi=\sum a_{j}\ind{E_{j}}\in L^{+}$ be simple.
Define the integral of $\phi$ w.r.t. $\mu$ by $\displaystyle \int\phi\d \mu=\sum a_{j}\mu(E_{j})$.
Let $A\in \mathcal{M}$. Then $\phi \ind{A}=\sum a_{j}\ind{A\cap E_{j}}$ is simple.
Define $\displaystyle\int_{A}\phi\d \mu=\int \phi \ind{A}\d \mu$.
Alternative notations:$$\int_{A}\phi=\int_{A}\phi\d \mu=\int _{A}\phi(x)\d \mu(x)=\int \phi \ind{A}\d \mu,\qquad \int=\int_{X}$$
