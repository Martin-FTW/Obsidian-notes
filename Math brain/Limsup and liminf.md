# Limsup and liminf
## Idea
1. When removing elements from a set, the sup can only decrease while inf can only increase, so limsup and liminf are asking "if we keep shrinking towards the limit point, what are the sup and inf of the remaining?"
1. Limsup is the sup of subsequential limits, and liminf is the inf of that
### Special characterization for real sequences
	Limsup is the sup of frequent terms, i.e. those which occur infinitely often; And liminf is the inf of that
For limsup:
- $x\geq\varlimsup x_{n}\iff x\geq x_{n}$ eventually, i.e. only finitely many $x_{n}>x$, thus: $\forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:\forall n \geq N:\varlimsup x_{n}+\varepsilon>x_{n}$
- $x\leq\varlimsup x_{n}\iff x\leq x_{n}$ frequently, i.e. infinitely many $x_{n}\leq x$, thus: $\forall \varepsilon>0:\exists(x_{n_{k}}):\forall k: \varlimsup x_{n}-\varepsilon<x_{n_{k}}$
- $x=\varlimsup x_{n}\iff x=\inf \set{b\in \mathbb{R}\given\forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:b+\varepsilon > x_{n}}$

Similarly for liminf:
- $x\leq\varliminf x_{n}\iff x\leq x_{n}$ eventually, i.e. only finitely many $x_{n}<x$, thus: $\forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:\forall n \geq N:\varliminf x_{n}-\varepsilon<x_{n}$
- $x\geq\varliminf x_{n}\iff x\geq x_{n}$ frequently, i.e. infinitely many $x_{n}\leq x$, thus: $\forall \varepsilon>0:\exists(x_{n_{k}}):\forall k: \varliminf x_{n}+\varepsilon>x_{n_{k}}$
- $x=\varliminf x_{n}\iff x=\sup \set{a\in \mathbb{R}\given\forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:a-\varepsilon < x_{n}}$

Hence $[\varliminf x_{n},\varlimsup x_{n}]$ is the smallest closed interval $I$ with the property that $x_{n}$ is eventually in $I$, i.e. only finitely many $x_{n}\notin I$, or $\exists N\in \mathbb{Z}_{>0}:\forall n\geq N:x_{n}\in I$
## Real sequence
Let $(x_{n})$ be a sequence $(a_n),(b_n)$ be sequences defined by $$\begin{align}
a_n&:=\inf\set{x_{n+k}}=\inf \set{x_k\given k\geq n}=\inf_{k\geq n}x_k\\ b_n&:=\sup\set{x_{n+k}}=\sup \set{x_k\given k\geq n}=\sup_{k\geq n}x_k
\end{align}$$for any $n\in\mathbb{N}$.
Define $$\begin{align}
\varliminf x_n=\lim (a_n)=\lim_{n}(\inf_{k}\set{x_{n+k}})=\lim_{n} \left(\inf_{k\geq n} x_k\right)\\\varlimsup x_n=\lim (b_n)=\lim_{n}(\sup_{k}\set{x_{n+k}})=\lim_{n} \left(\sup_{k\geq n} x_k\right)
\end{align}$$By bounded-monotone, we also have
$$
\begin{align}
\varliminf(x_{n})&=\sup\set{a_{n}}=\sup_{n}\set*{\inf_{k}\set{x_{n+k}}}=\sup_{n\in\mathbb{Z}_{>0}}\inf_{k\geq n} x_{k} \\
\varlimsup(x_{n})&= \inf\set{b_{n}}=\inf_{n}\set*{\sup_{k}\set{x_{n+k}}}=\inf_{n\in\mathbb{Z}_{>0}}\sup_{k\geq n}x_{k}
\end{align}
$$
