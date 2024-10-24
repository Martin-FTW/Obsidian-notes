# Inequalities
## Young's
Let $a,b>0$ and $p,q\in \opop{1}{\infty}$ be conjugate exponents.
Then $\displaystyle ab\leq \frac{a^{p}}{p}+\frac{b^{q}}{q}$
- "$=$" iff $a^{p}=b^{q}$.
## Holder's
Let $f,g\in \measurable$ and $p,q\in \clcl{1}{\infty}$ be conjugate exponents.
Then $\norm{fg}_{1}\leq \norm{f}_{p}\norm{g}_{q}$.
- "$=$" iff $\abs{f}^{p},\abs{g}^{q}$ are positively linearly dependent, i.e. $f\equiv 0\ae$ or $\exists \lambda \geq0:\abs{g}^{q}=\lambda \abs{f}^{p}\ae$
## Minkowsky
Let $f,g\in \mathcal{L}^{p}$ and $p\in \clcl{1}{\infty}$.
Then $\norm{f+g}_{p}\leq \norm{f}_{p}+\norm{g}_{p}$.
- "$=$" iff $\abs{f}^{p},\abs{g}^{q}$ are linearly dependent, i.e. $f\equiv 0\ae$ or $\exists \lambda \geq0:\abs{g}^{q}=\lambda \abs{f}^{p}\ae$
## Norm comparison
### Riemann-integrable
Let $f\in R\clcl{a}{b},1\leq p<r\leq \infty$.
Then $\norm{f}_{p}\leq(b-a)^{\frac{1}{p}-\frac{1}{r}}\norm{f}_{r}$ and $\not\exists C>0:\norm{f}_{r}\leq C\norm{f}_{p}$
### Finite-dimension
Let $x\in \mathbb{R}^{n},1\leq p<r\leq \infty$.
Then $\norm{x}_{p}\leq n^{\frac{1}{p}-\frac{1}{r}}\norm{x}_{r}$ and $\norm{x}_{r}\leq n^{\frac{1}{r}}\norm{x}_{p}$