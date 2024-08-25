Book: [[MATH3030]]
# Theorem (Structure of finitely generated abelian groups)
Every finitely generated abelian group $G$ is isomorphic to a direct sum of cyclic groups in the following forms:
$$\begin{align}
G&\cong G_{\text{free}}\oplus G_{\text{tor}} \\
&=\mathbb{Z}^{r}\oplus \bigoplus_{i=1}^{k}\mathbb{Z}_{p_{i}^{n_{i}}} \\
&=\mathbb{Z}^{r}\oplus \bigoplus_{i=1}^{k}\bigoplus_{j=1}^{\ell_{i}}\mathbb{Z}_{p_{i}^{n_{ij}}}  & \text{(Primary decomposition)}\\
&=\mathbb{Z}^{r}\oplus\bigoplus_{t=1}^{s}\mathbb{Z}_{d_{t}} & \text{(Invariant factor decomposition)}
\end{align}$$
where:
- $G_{\text{free}}=\mathbb{Z}^{r}$ is called the free part of $G$ and $r$ is called the rank of $G$
- $G_{\text{tor}}$ is called the torsion part of $G$, which is a finite abelian group.

By [[2078 T 6.4.3 (Classification of finite abelian groups)]], we have the primary decomposition of $G$:
- $p_{1}<p_{2}<\dots,p_{k}$ are prime numbers
- $n_{i1}\geq n_{i2}\geq\cdots\geq n_{i\ell_{i}}$ is a partition of $n_{i}$ for all $i$.
- $D\coloneqq\set{p_{i}^{n_{ij}}\given i\in\ii{1}{k},j\in\ii{1}{\ell_{i}}}$ are called the elementary divisors of $G$

By rewriting the order and using $\mathbb{Z}_{m}\times \mathbb{Z}_{n}\cong \mathbb{Z}_{mn}\iff \gcd(m,n)=1$, we have the invariant factor decomposition of $G$:
- $d_{1}\divides d_{2}\divides\cdots\divides d_{s}$ are integers $>1$.

Note that $\displaystyle \card{G_{\text{tor}}}=\prod_{n\in E}n=\prod_{i=1}^{k}\prod_{j=1}^{\ell_{i}}p_{i}^{n_{ij}}=\prod_{i=1}^{k}p^{n_{i}}=\prod_{t=1}^{s}d_{t}$ 
The equivalence of the two forms can be summarized by the following table:
$$\begin{array}{|c|c}
\hline p_{1}^{n_{11}} & p_{2}^{n_{21}} & \cdots & p_{i}^{n_{i1}} & \cdots \\
\hline p_{1}^{n_{12}} & p_{2}^{n_{22}} & \cdots & p_{i}^{n_{i2}} & \cdots \\
\hline \vdots & \vdots & \cdots & \vdots & \cdots \\
\hline p_{1}^{n_{1j}} & p_{2}^{n_{2j}} & \cdots & p_{i}^{n_{ij}} & \cdots \\
\hline \vdots & \vdots & \cdots & \vdots & \ddots
\end{array}$$
where 
- product of row $j$ gives $d_{s-j+1}$ 
- product of column $i$ gives $p_{i}^{n_{i}}$
- each row has increasing primes going left to right
- each column has decreasing powers going top to bottom

Final remark: there is a bijective correspondence between $\set{(P_{1},\dots,P_{n})\given P_{i}=(n_{i1},\dots,n_{i\ell_{i}}) \text{ is a partition for } n_{i}}$ and $\set{G\in \obj\mathsf{Ab}\given \card{G}=\prod p_{i}^{n_{i}} }$.