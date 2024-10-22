# Group definitions
Let $G$ be a group.
- finite: $\ord G=\card{G}$ is finite
- abelian: $\forall a,b\in G:ab=ba$
- cyclic: $\exists a\in G:\forall g\in G:\exists n\in \mathbb{Z}:g=a^{n}$
- finitely generated: $\exists A\subseteq G:G=\gen{A}$
- free: $\exists$ set $A$ s.t. $G\iso F(A)$.
- finitely presented: $\exists$ finite set $A$, finite $\mathcal{R}\subseteq F(A)$ s.t. $G=\gen{A|\mathcal{R}}$
- simple: $G$ has no proper nontrivial normal subgroups
- solvable: $G$ has a solvable series

Let $H\leq G$ be a subgroup
- $H$ normal: 
	- $\forall a\in G:aH=Ha$ (or subset)
	- $\forall a\in G:aHa^{-1}=H$ (or subset)
	- $\exists \varphi:G\to G'$ s.t. $H=\ker \varphi$
- $H$ maximal: $H\trianglelefteq G$ and
	- $\not\exists N\trianglelefteq G$ s.t. $M<N<G$
	- $\forall N\trianglelefteq G$, if $M\leq N$ then $M=N$
- 