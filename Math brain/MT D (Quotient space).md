Book: [[Munkres Topology (MT)]]
# Definition (Quotient space)
Let $X$ be a topological space.
Let $X^{*}$ be a partition of $X$ (i.e. disjoint subsets whose union is $X$)
i.e. the set of equivalence classes of some equivalence relation $\sim$.
Let $p:X\to X^{*}$ be the canonical projection map $p(x)=[x]_{\sim}$.
Let $\mathscr{T}$ be the quotient topology induced by $p$.
We call $(X^{*},\mathscr{T})$ a quotient space of $X$.

Note that any $U\subset X^{*}$ is a collection of equivalence classes, thus $p ^{-1}(U)$ is a union of all these equivalence classes.
Thus $U$ is open iff $\displaystyle \cup U\coloneqq\bigcup_{S\in U}S$ is open in $X$.