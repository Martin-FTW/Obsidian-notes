# Function approximations
## Stone-Weierstrass theorem
Let $f\in C\clcl{a}{b}$.
Then $\forall \varepsilon>0:\exists p\in P\clcl{a}{b}:\norm{f-p}_{\infty}<\varepsilon$
Constructive: Bernstein polynomial
### Finite trig
Moreover:
$\displaystyle \forall \varepsilon>0:\exists h=a_{0}+\sum_{k=1}^{n} (a_{k}\cos(kx)+b_{k}\sin(kx)):\norm{f-h}_{\infty}<\varepsilon$
## Riemann-integrable steps
Let $f\in R\clcl{a}{b}$.
Then $\forall \varepsilon>0:\exists$ step function $s:\clcl{a}{b}$ s.t. $s\leq f$ and $\displaystyle 0\leq \int_{a}^{b}(f-s)<\varepsilon$.
Constructive: Darboux lower sums
## Continuous steps
Let $s=\sum a_{j}\ind{I_{j}}:\clcl{a}{b}\to \mathbb{R}$ be a step function.
$\displaystyle \forall \varepsilon>0:\exists g\in C\clcl{a}{b}:\int_{a}^{b}\abs{s-g}<\varepsilon$
