Book: [[Folland Real Analysis (RAMT&TA)]]
# Theorem 1.14 (Every sigma-finite premeasure on an algebra can be uniquely extended to a measure on the generated sigma-algebra)
Let $X$ be a set and $\mathcal{A}\subseteq \power(X)$ be an algebra on $X$
Let $\mu_{0}:\mathcal{A}\to \clcl{0}{\infty}$ be a premeasure.
Let $\mathcal{M}=\sigma(\mathcal{A})$.
Then $\exists$ measure $\mu:\mathcal{M}\to \clcl{0}{\infty}$ that extends $\mu_{0}$, i.e. $\mu|_{A}=\mu_{0}$.
One such extension is given by the outer approximation $\mu^*$ in [[RAMT&TA P 1.13 (Outer approximation of a premeasure extends the premeasure to an outer measure)]].

If $\nu:\mathcal{M}\to \clcl{0}{\infty}$ is another measure that extends $\mu_{0}$, then $\forall E\in \mathcal{M}:\nu(E)\leq \mu^*(E)$ with equality when $\mu^*(E)<\infty$.
If $\mu_{0}$ is $\sigma$-finite, then $\mu^*$ is the unique extension of $\mu_{0}$ to a measure on $\mathcal{M}$.

