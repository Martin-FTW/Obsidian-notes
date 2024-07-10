Book: [[Munkres Topology (MT)]]
# Exercise 13.7
Consider the following topologies on $\mathbb{R}$:
1. $\mathscr{T}_{1}$: standard topology
2. $\mathscr{T}_{2}$: the topology of $\mathbb{R}_{K}$
3. $\mathscr{T}_{3}$: the finite complement topology
4. $\mathscr{T}_{4}$: The upper limit topology, with basis containing all $(a,b]$
5. $\mathscr{T}_{5}$: the topology having all $(-\infty,a)$ as basis.

Which contain which?
## Solution
$\mathscr{T}_{3},\mathscr{T}_{5}\subset \mathscr{T}_{1}\subset \mathscr{T}_{2}\subset \mathscr{T}_{4}$, $\mathscr{T}_{3},\mathscr{T}_{5}$ incomparable.
#### Proof
We have $\mathscr{T}_{2}$ properly contains $\mathscr{T}_{1}$.

Every open set in $\mathscr{T}_{3}$ is open in $\mathscr{T}_{1}$, but $(0,1)$ is not open in $\mathscr{T}_{3}$, hence $\mathscr{T_{1}}$ is strictly finer than $\mathscr{T}_{3}$

Every open set in $\mathscr{T}_{5}$ is in the form $(-\infty,a)$, thus is open in $\mathscr{T}_{1}$. 
However, $(0,1)$ is not open in $\mathscr{T}_{5}$, thus $\mathscr{T}_{1}$ is strictly ffiner than $\mathscr{T}_{5}$.

$\mathbb{R}\setminus \set{0}$ is open in $\mathscr{T}_{3}$ but not $\mathscr{T}_{5}$, and $(-\infty,0)$ is open in $\mathscr{T}_{5}$ but not $\mathscr{T}_{3}$.
Hence $\mathscr{T}_{3},\mathscr{T}_{5}$ are not comparable.

$\forall x\in X$, let $x\in (a,b)\in \mathscr{B}_{4}$.
Then $x\in(a,x]\subset(a,b)$.

$\forall x\in X$, let $x\in(a,b)\setminus K\in \mathscr{B}_{2}$.
If $x\leq 0$ then $x\in(a,0] \subset(a,b)\setminus K$.
If $x>0$ then $\exists N$ s.t. $\frac{1}{N+1}<x< \frac{1}{N}$, thus $x\in( \frac{1}{N+1},x]\subseteq (a,b)\setminus K$.
Hence $\mathscr{T}_{4}$ is finer than $\mathscr{T}_{2}$.

