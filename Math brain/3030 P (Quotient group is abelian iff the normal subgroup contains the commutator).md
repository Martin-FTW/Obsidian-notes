Book: [[MATH3030]]
# Proposition (Quotient group is abelian iff the normal subgroup contains the commutator)
Let $G$ be a group.
Then $[G,G]\unlhd G$ and $\forall N\unlhd G$, $G/N$ is abelian iff $N>[G,G]$.
#### Proof
Let $S=\set{aba^{-1}b^{-1}\given a,b\in G}$
Let $aba^{-1}b^{-1}\in S$ and $g\in G$.
Then $gaba^{-1}b^{-1}g^{-1}=(gag^{-1})(gbg^{-1})(gag^{-1})^{-1}(gbg^{-1})^{-1}\in S$.
Hence $gSg^{-1}\subseteq S$ for all $g\in G$.
Thus $g\gen{S}g^{-1}\subseteq S$ for all $g\in G$.
It follows that $[G,G]\unlhd G$.

Now TFAE:
1. $G/N$ is abelian
2. $(aN)(bN)=(bN)(aN)$ for all $a,b\in G$.
3. $ab\in baN$ for all $a,b\in G$
4. $aba^{-1}b^{-1}=ab(ba)^{-1}\in N$ for all $a,b\in G$
5. $S\subseteq N$
6. $[G,G]=\gen{S}\leq N$.