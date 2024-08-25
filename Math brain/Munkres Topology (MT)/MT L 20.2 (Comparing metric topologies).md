Book: [[Munkres Topology (MT)]]
# Lemma 20.2 (Comparing metric topologies)
Let $d,d'$ be two metrics on the set $X$.
Let $\mathscr{T},\mathscr{T}'$ be the induced topologies by $d,d'$ on $X$.
Then $\mathscr{T}'$ is finer than $\mathscr{T}$ iff
- $\forall x\in X:\forall \epsilon>0:\exists \delta>0:B_{d'}(x,\delta)\subset B_{d}(x,\epsilon)$
#### Proof
$(\implies):$ Suppose $\mathscr{T}'$ is finer than $\mathscr{T}$. Let $x\in X,\epsilon>0$.
Then $B_{d}(x,\epsilon)$ is a basis element for $\mathscr{T}$ containing $x$.
Thus $\exists$ basis element $B_{d'}(y,\delta')$ for $\mathscr{T}'$ s.t. $x\in B_{d'}(y,\delta')\subset B_{d}(x,\epsilon)$. 
Since $x\in B_{d'}(y,\delta')$, we can find $\delta>0$ s.t. $x\in B_{d'}(x,\delta)\subset B_{d'}(y,\delta')\subset B_{d}(x,\epsilon)$.
$(\impliedby):$ Suppose that statement.
Let $B_{d}(y,\epsilon)$ be a basis element in $\mathscr{T}$ containing $x$.
Then we can find $\epsilon'>0$ s.t. $x\in B_{d}(x,\epsilon')\subset B_{d}(y,\epsilon)$.
Now $\exists \delta>0$ s.t. $B_{d'}(x,\delta)\subset B_{d}(x,\epsilon')$ by assumption.
Hence there is a basis element for $\mathscr{T}'$ that satisfies $x\in B_{d'}(x,\delta)\subset B_{d}(x,\epsilon')$.
It follows that $\mathscr{T}'$ is finer than $\mathscr{T}$.
