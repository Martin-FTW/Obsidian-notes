Book: [[Munkres Topology (MT)]]
# Lemma 31.1 (Characterization of regularity and normality for T1 spaces)
Let $X$ be a $T_{1}$ space, i.e. all singletons are closed.
Then
1. $X$ is regular iff $\forall x\in X,$ nbhd $U\ni x$, $\exists$ nbhd $V\ni x$ s.t. $\overline{V}\subseteq U$
2. $X$ is normal iff $\forall$ closed set $A$, open set $U\supseteq A$, $\exists$ open set $V\supseteq A$ s.t. $\overline{V}\subseteq U$

#### Proof
$1.(\implies):$ Suppose $X$ is regular. 
Let $x\in X$ and nbhd $U\ni x$. Then $X\setminus U$ is closed.
Hence $\exists$ nbhd $V\ni x$, open set $W\supseteq X\setminus U$ s.t. $V\cap W=\emptyset$
Now every $y\in X\setminus U$ has a nbhd disjoint from $V$, namely $W$, hence $y\notin \overline{V}$.
It follows that $X\setminus U\subseteq \overline{V}$, thus $\overline{V}\subseteq U$.
$1.(\impliedby):$ Suppose $\forall x\in X$, nbhd $U\ni x$, $\exists$ nbhd $V\ni x$ s.t.