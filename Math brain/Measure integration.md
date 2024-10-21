# Measure integration
Let $(X,\mathcal{M},\mu)$ be a measure space.
Let $(Y,\mathcal{N})\in \set{(\overline{\mathbb{R}},\mathcal{B}(\overline{\mathbb{R}})),(\mathbb{C},\mathcal{B}(\mathbb{C}))}$
Let $A\subseteq X$
## Extended real
Define
- $f:X\to Y$ is $(\mathcal{M},\mathcal{N})$-measurable if $\forall E\in \mathcal{N}:f^{-1}(E)\in \mathcal{M}$
- $\phi:X\to Y$ is simple if $\im \phi$ is finite, or $\displaystyle \phi=\sum a_{j}\ind{E_{j}}$.
- $L^{+}(X,\mathcal{M},\mu)=\set{f:X\to \clcl{0}{\infty}\given f\text{ is measurable}}$
- $L(X,\mathcal{M},\mu)=\set*{f:X\to \overline{\mathbb{R}}\given \begin{array}{}f\text{ is measurable and }\\\int f^{+}<\infty \text{ or }\int f^{-}<\infty\end{array}}$
- $f:X\to \overline{\mathbb{R}}$ is integrable if $\int f^{+}<\infty$ and $\int f^{-}<\infty$
- $f:X\to \mathbb{C}$ is integrable if $\int\abs{f}<\infty$
- $f:X\to \mathbb{C}$ is integrable on $A$ if $\int_{A}\abs{f}<\infty$
- $L^{1}(X,\mathcal{M},\mu)=\set*{f:X\to \mathbb{C}\given f\text{ is integrable}}/\set{f=g\ae}$

### Simple approximation
Let $f\in L^{+}$.
Then $\exists$ simple functions $\phi_{n}:X\to \clcl{0}{\infty}$ s.t. 
1. $\forall j\in \mathbb{Z}_{>0}:0\leq \phi_{j}\leq \phi_{j+1}\leq f$
2. $\phi_{n}\to f$ pointwise
3. $\forall A\subseteq X$: if $f\vert_{A}$ is bounded then $\phi_{n}\vert_{A}\to f\vert_{A}$ uniformly 
### Construction
Notation: $\displaystyle \int\square=\int\square\d \mu=\int\square(x)\d \mu(x)\ ,\quad \int=\int_{X}\ ,\quad\int_{A}\square=\int_{X}\square\cdot \ind{A}$
- $\displaystyle \phi=\sum a_{j}\ind{E_{j}}\in L^{+}:\int\phi=\sum a_{j}\mu(E_{j})$
- $f\in L^{+}:\displaystyle \int f=\sup \set*{\int \phi \given 0\leq \phi \leq f,\phi \text{ simple}}$
- $\displaystyle f\in L:\int f=\int f^{+}-\int f^{-}$
- $\displaystyle f\in L^{1}:\int f=\int \Re f+i \int \Im f$
### Properties on positive
Let $f,g\in L^{+}$ and $(f_{n})$ be a sequence in $L^{+}$
- $A\mapsto \int_{A}1$ is a measure on $\mathcal{M}$
- $\forall c\geq 0:\int cf=c\int f$ 
- $f\leq g\implies\int f \leq \int g$ (monotone)
- $f_{n}\uparrow f\implies\int f=\int \lim(f_{n})=\lim \int f_{n}$ (MCT)
- $f=\sum f_{n}\implies\int f=\int\sum f_{n}=\sum \int f_{n}$ (Additivity)
- $\int f=0\iff f=0\ae$
- $\int f=\int g\iff f=g\ae$
- $f_{n}\uparrow f\ae\implies \int f=\lim \int f_{n}$ (MCTae)
- $\int\liminf(f_{n})\leq\liminf\left( \int f_{n} \right)$ (Fatou)
- $f\to f_{n}\ae\implies \int f\leq \liminf\left( \int f_{n} \right)$
- $\int f<\infty\implies \mu([f=\infty])=0,[f>0]$ is $\sigma$-finite.
### Properties on L1
Let $f,g\in L^{1}$ and $(f_{n})$ be a sequence in $L^{1}$.
- $\abs{\int f}\leq \int\abs{f}$
- $[f\neq 0]$ is $\sigma$-finite
- For $\im f,\im g\subseteq \mathbb{R}$: $f\leq g\ae\implies \int f\leq \int g$
- $[f]_{\sim}=[g]_{\sim}\begin{cases}\iff\forall E\in \mathcal{M}:\int_{E}f=\int_{E}g\\\iff \int\abs{f-g}=0\\\iff f=g\ae\end{cases}$
- $f_{n}\to f\ae$ and $\exists g\in L^{1}\cap L^{+}:\forall n\in \mathbb{Z}_{>0}:\abs{f_{n}}\leq g\ae$
  $\implies f\in L^{1},\int f=\lim \int f_{n}$ (DCT)
- $\sum \int\abs{f_{n}}<\infty\implies \sum f_{n}<\infty\ae,\int\sum f_{n}=\sum \int f_{n}$
- Let $F:X\times \opop{a}{b}\to \mathbb{R}$ s.t. $\begin{cases}\forall t\in \opop{a}{b}:F(\cdot,t)\in L^{1}\\\displaystyle \forall(x,t)\in X\times \opop{a}{b}:\frac{ \partial F}{ \partial t }(x,t)\text{ exists}\\\displaystyle \exists g\in L^{1}:\forall(x,t)\in X\times \opop{a}{b}:\abs*{\frac{ \partial F}{ \partial t }(x,t)}\leq g(x)\end{cases}$
  $\displaystyle \implies t\mapsto \int\frac{ \partial F }{ \partial t }(x,t)\d \mu(x)$ is differeiable on $\opop{a}{b}$ and $\displaystyle\frac{d}{dt}\int F(x,t)\d \mu(x)=\int\frac{ \partial F}{ \partial t}(x,t)\d \mu(x)$
## Relation with Riemann
- Let $-\infty<a<b<\infty$ and $f:\clcl{a}{b}\to \mathbb{R}$ be Riemann-integrable.
  $\implies f$ is lebesgue measurable and integrable, with $\displaystyle\int_{a}^{b}f(x)\d x=\int_{\clcl{a}{b}}f\d \mu_{L}$
- Let $a\in \mathbb{R}$ and $f:\clop{a}{\infty}\to \mathbb{R}$ be measurable.
  Suppose $\forall c\in \opop{a}{\infty}:f\in R\clcl{a}{c}$.
  Then $f\in L^{1}\clop{a}{\infty}\iff\displaystyle\lim_{c \to \infty}\int_{a}^{c}\abs{f(x)}\d x<\infty$.
  In this case, $\displaystyle\int_{a}^{\infty}f(x)\d x=\int_{\clop{a}{\infty}}f\d \mu_{L}$