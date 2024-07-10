# Bachmann-Landau notation
For expressions $\varphi(x,O(h(x))),\psi(x,O(g(x)))$, we write $\varphi(x,O(h(x)))=\psi(x,O(g(x)))$ as $x\to a$ if 
- $\forall f_{1}\in O_{a}(h):\exists f_{2}\in O_{a}(g):\varphi(x,f_{1}(x))=\psi(x,f_{2}(x))$, that is $\varphi(x,O_{a}(h))\subseteq\psi(x,O_{a}(g))$

If $\varphi(x)$ is not dependent on $O(h(x))$, we write $\varphi(x)=\psi(x,O(g(x)))$ as $x\to a$ if 
- $\exists f\in O_{a}(g):\varphi(x)=\psi(x,f(x))$, that is $\varphi(x)\in \psi(x,O_{a}(g))$

All notations defined below:
## General
Let $X$ be a subspace of a topological space $\tilde{X}$.
Let $(Y,\norm{\cdot})$ be a normed vector space.
Let $g,h:X\to Y$ be functions.
Let $a\in \tilde{X}$ be a limit point of $X$.
Define the big $O$ notation by the following equivalent statements:
- $O_{a}(g)=\set{f\in Y^{X}\given \exists M>0:\exists \text{nbhd }U\ni a:\forall x\in U\cap X:\norm{f(x)}\leq M\norm{g(x)}}$

Define the little $O$ notation by the following equivalent statements:
- $o_{a}(g)=\set{f\in Y^{X}\given\forall \varepsilon>0:\exists \text{nbhd }U\ni a:\forall x\in U\cap X:\norm{f(x)}\leq \varepsilon \norm{g(x)}}$

## Real
Restrict $\tilde{X},Y$ to $\mathbb{R}$.
Let $X$ be a subspace of $\mathbb{R}$.
Let $g,h:X\to \mathbb{R}$ be functions.
Let $a\in \mathbb{R}$ be a limit point of $X$.
Define the big $O$ notation by the following equivalent statements:
- $O_{a}(g)=\set{f\in \mathbb{R}^{X}\given \exists M>0:\exists \delta>0:\forall x\in \oo{a-\delta}{a+\delta}\cap X\setminus \set{a}:\abs{f(x)}\leq M\abs{g(x)}}$

Define the little $O$ notation by the following equivalent statements:
- $o_{a}(g)=\set{f\in \mathbb{R}^{X}\given \forall \varepsilon>0:\exists \delta>0:\forall x\in \oo{a-\delta}{a+\delta}\cap X\setminus \set{a}:\abs{f(x)}\leq M\abs{g(x)}}$

## Sequence
Restrict $\tilde{X}$ to $\mathbb{Z}_{>0}\cup \set{\infty}$, $X$ to $\mathbb{Z}_{>0}$ and $a$ to $\infty$ (the only limit point of $\mathbb{Z}_{>0}$).
Let $g,h:\mathbb{Z}_{>0}\to Y$ be functions.
Define the big $O$ notation by the following equivalent statements:
- $O_{\infty}(g)=\set{f\in Y^{\mathbb{Z}_{>0}}\given \exists M>0:\exists N\in \mathbb{Z}_{>0}:\forall n\geq N:\norm{f(n)}\leq M\norm{g(n)}}$

Define the little $O$ notation by the following equivalent statements:
- $o_{\infty}(g)=\set{f\in Y^{\mathbb{Z}_{>0}}\given \forall \varepsilon>0:\exists N\in \mathbb{Z}_{>0}:\forall n\geq N:\norm{f(n)}\leq M\norm{g(n)}}$

