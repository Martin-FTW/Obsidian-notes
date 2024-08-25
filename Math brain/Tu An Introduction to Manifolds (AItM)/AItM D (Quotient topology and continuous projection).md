Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Quotient topology and continuous projection)
Let $S$ be a topological space and $\sim$ be an equivalence relation on $S$.
Denote by $\pi:S\to S/{\sim}$ the natural projection map.
Define the quotient topology on $S/{\sim}$ by declaring that $U\subseteq S/{\sim}$ is open iff $\pi ^{-1}(U)$.
Now let $Y$ be a topological space and $f:S\to Y$ be a function.
Suppose $f$ is constant on each equivalence class, i.e. $\forall p\in S:\exists c_{p}\in Y:f|_{[p]_{\sim}}\equiv c_{p}$. 
Then $f$ induces a map $\bar{f}:S/{\sim}\to Y$ by $\forall p\in S:\bar{f}([p]_{\sim})=f(p)$ by [[AC0 T I.2.7 (Canonical decomposition of a function)]].
