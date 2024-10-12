Book: [[Folland Real Analysis (RAMT&TA)]]
# Theorem 1.16 (Every increasing right-continuous function induces a unique Borel measure on reals, every Borel measure induces a distribution function)
Let $F:\mathbb{R}\to \mathbb{R}$ be an increasing right-continuous function.
Then $\exists$ unique Borel measure $\mu_{F}:\mathcal{B}(\mathbb{R})\to \clcl{0}{\infty}$ s.t. $\forall a,b\in \mathbb{R}:\mu_{F}(\opcl{a}{b})=F(b)-F(a)$.
If $G:\mathbb{R}\to \mathbb{R}$ is another increasing right-continuous function, then $\mu_{F}=\mu_{G}\iff \exists c\in \mathbb{R}: F-G\equiv c$ 

Conversely, let $\mu:\mathcal{B}(\mathbb{R})\to \clcl{0}{\infty}$ be a Borel measure.
Suppose $\mu$ is finite on all bounded Borel sets.
Then its distribution function $F_{\mu}:\mathbb{R}\to \mathbb{R}$ defined by $F_{\mu}(x)=\begin{cases}\mu(\opcl{0}{x})&x>0\\0&x=0\\-\mu(\opcl{-x}{0})&x>0\end{cases}$ is increasing and right-continuous.
Moreover, $\mu=\mu_{F_{\mu}}$.