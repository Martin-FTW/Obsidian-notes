Book: [[Munkres Topology (MT)]]
# Lemma 13.4
$\mathbb{R}_{\ell}$ and $\mathbb{R}_{K}$ are finer than $\mathbb{R}$ but are not comparable to each other.
#### Proof
Denote the bases by $\mathscr{B},\mathscr{B}_{\ell},\mathscr{B}_{K}$ respectively.
We use [[MT L 13.3 (Finer topology basis)]]:
Let $x\in X$ and $(a,b)\in \mathscr{B}$ s.t. $x\in (a,b)$.
Then $x\in[x,b)\subset(a,b)$.
Since $[x,b)\in \mathscr{B}_{\ell}$ and $(a,b)\in \mathscr{B}_{K}$, we have $\mathbb{R}_{\ell},\mathbb{R}_{K}$ are finer than $\mathbb{R}$.

Since $[0,1)$ is open in $\mathbb{R}_{\ell}$ but not $\mathbb{R}$, $\mathbb{R}$ is not finer than $\mathbb{R}_{\ell}$.

Take $0\in(-1,1)\setminus K\in \mathscr{B}_{K}$.
Now if there is some $(a,b)\in \mathscr{B}$ s.t. $0\in(a,b)\subset(-1,1)\setminus K$, then by Archimedean property $\exists N\in \mathbb{Z}_{>0}$ s.t. $N>1/b$.
Now $\frac{1}{N}\in(a,b)$ but $\frac{1}{N}\notin(-1,1)\setminus K$. Contradiction.
It follows that no basis element in $B$ contains $0$.

Take $0\in(-1,1)\setminus K\in \mathscr{B}_{K}$.
Now if there is some $[a,b)\in \mathscr{B}_{\ell}$ s.t. $0\in[a,b)\subset(-1,1)\setminus K$, then $a\leq 0<b$.
By Archimedean property $\exists N\in \mathbb{Z}_{>0}$ s.t. $N>1/b$.
Now $\frac{1}{N}\in[a,b)$ but $\frac{1}{N}\notin(-1,1)\setminus K$. Contradiction.
It follows that $\mathbb{R}_{\ell}$ is not finer than $\mathbb{R}_{K}$.

Since $[2,3)$ is open in $\mathbb{R}_{\ell}$ but not $\mathbb{R}_{K}$, $\mathbb{R}_{K}$ is not finer than $\mathbb{R}_{\ell}$.
