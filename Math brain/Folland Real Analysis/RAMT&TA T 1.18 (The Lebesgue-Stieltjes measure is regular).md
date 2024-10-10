Book: [[Folland Real Analysis Modern Techniques and Their Application (RAMT&TA)]]
# Theorem 1.18 (The Lebesgue-Stieltjes measure is regular)
Let $F:\mathbb{R}\to \mathbb{R}$ be an increasing right-continuos function.
Let $\mu:\mathcal{M}_{\mu}\to \clcl{0}{\infty}$ the Lebesgue-Stieltjes measure associated to $F$.
Then $\mu$ is regular. i.e. $\forall E\in \mathcal{M}_{\mu}:$$$\begin{align}\mu(E)&=\inf \set{\mu(U)\given E\subseteq U,U\text{ open}}\\&=\sup \set{\mu(K)\given K\subseteq E,K\text{ compact}}\end{align}$$
#### Proof
Let $\varepsilon>0$. Then $\exists$ intervals $\opop{a_{j}}{b_{j}}$ covering $E$ s.t. $\mu(E)+\varepsilon\geq \sum \mu(\opop{a_{j}}{b_{j}})$ by [[RAMT&TA L 1.17 (Lebesgue-Stieltjes measure can use open covering instead of h-intervals)]].
Now $\cup \opop{a_{j}}{b_{j}}$ is open and contains $E$, and $\mu(E)+\varepsilon \geq \mu(U)$.
Since $\mu(E)$ is an lower bound by $\mu$ monotone, we have $\mu$ is outer regular.

Now denote $L=\sup \set{\mu(K)\given K\subseteq E,K\text{ compact}}$. 
Then $L\leq \mu(E)$ by $\mu$ monotone.
1. If $E$ is bounded and closed, then its compact, thus $\mu(E)=L$ by $\mu$ monotone.
2. If $E$ is bounded and not closed, then we have $\overline{E}$ is closed, thus $\overline{E}\in \mathcal{M}_{\mu}$.
Hence $\overline{E}\setminus E\in \mathcal{M}_{\mu}$.
By above, $\forall \varepsilon>0$ we can choose some open $U$ containing $\overline{E}\setminus E$ s.t. $\mu(U)\leq \mu(\overline{E}\setminus E)$.
Now $K\coloneqq \overline{E}\setminus U$ is a closed and bounded, thus compact with $K\subseteq E$.
Note that $K=\overline{E}\setminus U=((\overline{E}\cap E)\cup(\overline{E}\setminus E))\setminus U=(E\setminus U)\cup \emptyset=E\setminus U$ by $\overline{E}\setminus E\subseteq U$.
Hence
$\mu(K)=\mu(E\setminus U)$
$=\mu(E)-\mu(E\cap U)$
$=\mu(E)-\mu(U)+\mu(U\setminus E)$
$\geq \mu(E)+\varepsilon$

3. If $E$ is unbounded, define $E_{j}=E\cap \clcl{-j}{j}$.
Note $E_{j}$ increases to $E$.
Hence $\lim \mu(E_{j})=\mu(E)$ by continuity from below.
Let $\varepsilon>0$. Note that $E_{n}\in \mathcal{M}_{\mu}$ is bounded for all $n$.
By above, $\exists K_{j}$ compact, $K_{j}\subseteq E_{j}$, and $\displaystyle \mu(E_{j})-\frac{\varepsilon}{j}\leq \mu(K_{j})\leq \mu(E_{j})$.
By squeeze theorem, $\lim \mu(K_{j})=\mu(E)$