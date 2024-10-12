Book: [[Folland Real Analysis (RAMT&TA)]]
# Theorem 1.9 (Every measure extends uniquely to a complete measure)
Let $(X,\mathcal{M},\mu)$ be a measure space.
Let $\mathcal{N}=\set{N\in \mathcal{M}\given\mu(N)=0}$ be the collection of null sets.
Let $\mathcal{F}=\set{F\in \power(N)\given N\in \mathcal{N}}$ be the collection of subsets of null sets.
Let $\overline{\mathcal{M}}=\set{E\cup F\given E\in \mathcal{M},F\in \mathcal{F}}=\set{E\cup F\given E\in \mathcal{M},F\subseteq N\in \mathcal{N}}$.
Then $\overline{M}$ is a $\sigma$-algebra and $\exists$ unique extension $\overline{\mu}:\overline{\mathcal{M}}\to \mathbb{R}$ s.t. $(X,\overline{M},\overline{\mu})$ is a complete measure space.
We call $\overline{\mu}$ the completion of $\mu$ and $\overline{\mathcal{M}}$ the completion of $\mathcal{M}$.