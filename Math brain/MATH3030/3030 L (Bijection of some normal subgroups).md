Book: [[MATH3030]]
# Lemma (Bijection of some normal subgroups)
Let $N\unlhd G$.
Let $\pi_{N}: G\to G/N$ be the canonical projection $\pi_{N}(g)=gN$.
Let $\Pi_{N}:\set{L\given N\leq L\unlhd G}\to \set{K\given K\unlhd G/N}$ be $\Pi_{N}(L)=\pi_{N}(L)$.
Then $\Pi_{N}$ is a bijection.
#### Proof
Let $L\in \set{L\given N\leq L\unlhd G}$. Then $\pi_{N}(L)\unlhd \pi_{N}(G)=G/N$ by [[2078 P 5.3.8 (Group homo normal subgroup)]]
Let $g\in \pi_{N}^{-1}(\pi_{N}(L))$. Then $\exists aN\in \pi_{N}(L)$ s.t. $aN=\pi_{N}(g)=gN$.
Now $a\in L$, thus $ga^{-1}\in N\leq L$.
Hence $g=(ga^{-1})(a)\in L$, thus $\pi_{N}^{-1}(\pi_{N}(L))\subseteq L$.
The converse is by definition of functions.
It follows that $\Pi_{N}$ is an injection.
Now let $K\unlhd G/N$. $\pi_{N}^{-1}(K)\unlhd G$ by [[2078 P 5.3.8 (Group homo normal subgroup)]].
Also, $N=\pi_{N}^{-1}(\set{e})\subseteq \pi_{N}^{-1}(K)$. Hence $N\leq \pi_{N}^{-1}(K)$.
Now $N\leq \pi_{N}^{-1}(K)\unlhd G$.
Since $\pi_{N}$ is surjective, we have $\pi_{N}(\pi_{N}^{-1}(K))=K$.
It follows that $\Pi_{N}$ is surjective.