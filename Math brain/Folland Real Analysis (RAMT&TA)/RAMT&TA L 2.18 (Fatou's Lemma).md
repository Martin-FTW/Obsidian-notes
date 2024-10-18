Book: [[Folland Real Analysis (RAMT&TA)]]
# Lemma 2.18 (Fatou's Lemma)
Let $(X,\mathcal{M},\mu)$ be a measure space.
Denote $L^{+}=\set{f:X\to \clcl{0}{\infty}\given f\text{ is measurable}}$.
Let $(f_{n})$ be a sequence in $L^{+}$.
Then $\displaystyle\int\liminf(f_{n})\leq\liminf \int f_{n}$
#### Proof
Let $\displaystyle g_{n}=\inf_{k\geq n}f_{k}$. Then $g_{n}$ is increasing and $\liminf(f_{n})=\sup \set{g_{n}}=\lim(g_{n})$.
By definition, $\forall n\in \mathbb{Z}_{>0}:\forall k\geq n:g_{n}\leq f_{k}$.
Hence $\int g_{n}\leq \int f_{k}$ by monotone.
Thus $\displaystyle \forall n\in \mathbb{Z}_{>0}:\int g_{n}\leq \inf_{k\geq n}\int f_{k}$.
Now $\displaystyle\int\liminf(f_{n})$ 
$=\int\lim(g_{n})$
$=\lim\int g_{n}$ by MCT
$\displaystyle \leq \lim_{n}\inf_{k\geq n}\int f_{k}$ 
$\displaystyle =\liminf f_{n}$.