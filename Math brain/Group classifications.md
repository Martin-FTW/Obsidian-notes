# Group classifications
Let $G$ be a group
## Cyclic
Suppose $G$ is cyclic.
If $G$ is infinite, then $G\iso \mathbb{Z}$
If $G$ is finite, then $G\iso C_{n}=\mathbb{Z}/n\mathbb{Z}\iso(\mathbb{Z}_{n},+_{n})$.
## Finite abelian
Suppose $G$ is finite abelian.
### Primary decomposition 
Then $\displaystyle G\iso \prod_{u=1}^{v}C_{q_{u}}=\prod_{i=1}^{k}\prod_{j=1}^{\ell_{i}}C_{p_{i}^{n_{ij}}}\iso \prod_{t=1}^{s}C_{d_{t}}$, where $G$ uniquely determines:
- prime powers $q_{1},\dots,q_{v}$ called *elementary divisors* of $G$,
- primes $p_{1}<\cdots<p_{k}$, and
- a partition of $n_{i}=\sum \set{n_{i,1}\geq n_{i,2}\geq \cdots\geq n_{i,\ell_{i}}}$ for each $i$
- integers $1<d_{1}\divides d_{2}\divides\cdots\divides d_{s}$ called *invariant factors* of $G$

Note that
- $\displaystyle \card{G}=\prod_{u=1}^{v}q_{u}=\prod_{i=1}^{k} p_{i}^{n_{i}}=\prod_{i=1}^{k}\prod_{j=1}^{\ell_{i}}p_{i}^{n_{ij}}=\prod_{t=1}^{s}d_{t}$
- $\displaystyle \card{G}=\prod_{i=1}^{k} p_{i}^{n_{i}}$ is the unique prime factorization of $\card{G}$ 
- $\displaystyle t=\sum_{i=1}^{k}\ell_{i}$ and $q_{u}=p_{i}^{n_{ij}}$ for some $i,j$

The equivalence of the two forms can be summarized by the following table:
$$\begin{array}{r}
\phantom{p_{i}^{n_{ij}}} d_{s}=\prod\\\phantom{p_{i}^{n_{ij}}} d_{s-1}=\prod\\\phantom{p_{i}^{n_{ij}}}\vdots\quad\;\ \\ d_{s-j+1}=\prod\\\phantom{p_{i}^{n_{ij}}} \vdots\quad\;\ 
\end{array}
\begin{array}{|c|c}
\hline p_{1}^{n_{11}} & p_{2}^{n_{21}} & \cdots & p_{i}^{n_{i1}} & \cdots \\
\hline p_{1}^{n_{12}} & p_{2}^{n_{22}} & \cdots & p_{i}^{n_{i2}} & \cdots \\
\hline \vdots & \vdots & \cdots & \vdots & \cdots \\
\hline p_{1}^{n_{1j}} & p_{2}^{n_{2j}} & \cdots & p_{i}^{n_{ij}} & \cdots \\
\hline \vdots & \vdots & \cdots & \vdots & \ddots
\end{array}$$
where 
- product of row $j$ gives $d_{s-j+1}$ 
- product of column $i$ gives $p_{i}^{n_{i}}$
- each row has increasing primes $p_{i}$ going left to right
- each column has decreasing powers $n_{ij}$ going top to bottom
## Finitely generated abelian
Suppose $G$ is finitely generated.
Then $G\iso G_{\text{free}}\times G_{\text{tor}}\iso \mathbb{Z}^{r}\times G_{\text{tor}}$, where $G$ uniquely determines:
- its free part $G_{\text{free}}\iso \mathbb{Z}^{r}$ where $r$ is called the rank of $G$, and
- its torsion part $G_{\text{tor}}$, which is a finite abelian group