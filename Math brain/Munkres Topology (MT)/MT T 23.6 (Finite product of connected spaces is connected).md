Book: [[Munkres Topology (MT)]]
# Theorem 23.6 (Finite product of connected spaces is connected)
#### Proof
Let $X,Y$ be connected spaces.
Take any $a\times b\in X\times Y$.
Then $X \times \set{b}\cong X$ is connected and $\set{x}\times Y\cong Y$ is connected for all $x\in X$.
Now $T_{x}\coloneqq(X\times \set{b})\cup(\set{x}\times Y)$ is connected as they have a common point $x \times b$ by [[MT T 23.3 (Union of connected subspaces with a common point is connected)]].
Hence $\displaystyle X\times Y=\bigcup_{x\in X} T_{x}$ is connected as all $T_{x}$ have a common point $a\times b$ by [[MT T 23.3 (Union of connected subspaces with a common point is connected)]].
