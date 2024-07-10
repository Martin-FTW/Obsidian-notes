Book: [[MATH2078]]
# Definition (Algebraic and transcendental)
Let $E/F$ be a field extension.
Let $\alpha\in E$.
Let $\phi_{\alpha}:F[x]\to E$ be the evaluation map $\phi_{\alpha}(f)=f(\alpha)$.
Then $\phi_{\alpha}|_{F}=\id_{F}$.
Define $F[\alpha]=\im\phi_{\alpha}$ and $F(\alpha)=\mathrm{Frac}(F[\alpha])$.
- We say $\alpha$ is transcendental over $F$ if $\ker\phi_{\alpha}=\set{0}$, i.e. $\alpha$ is not a root of any nonzero polynomial in $F[x]$. Note that $F[x]\cong F[\alpha]$ in this case.
- We say $\alpha$ is algebraic over $F$ if $\ker\phi_{\alpha}\neq \set{0}$, i.e. $\alpha$ is a root of some nonzero polynomial in $F[x]$.
  Since $F$ is a field, $F[x]$ is a PID, thus $\exists p\in F[x]:\ker\phi_{\alpha}=(p)$.
  Note that $F[x]/(p)\cong F[\alpha]=F(\alpha)$ in this case.