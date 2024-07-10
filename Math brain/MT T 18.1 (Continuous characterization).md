Book: [[Munkres Topology (MT)]]
# Theorem 18.1 (Continuous characterization)
Let $X,Y$ be topological spaces.
Let $f:X\to Y$.
Then TFAE:
1. $f$ is continuous
2. $\forall A\subset X:f(\bar{A})\subset \overline{f(A)}$
3. $\forall$ closed $B\subset Y$, $f^{-1}(B)$ is closed in $X$
4. $\forall x\in X:\forall$ nbhd $V$ of $f(x)$, $\exists$ nbhd $U$ of $x$ s.t. $f(U)\subset V$, 
   i.e. $f$ is continuous at $x$.

#### Proof
$1\implies 2:$ Suppose $f$ is cts. Let $A\subset X$ and $y\in f(\bar{A})$
Then $\exists x\in \bar{A}$ s.t. $y=f(x)$.
Now let $V$ be a nbhd of $y$. Then $f^{-1}(V)$ is open by continuity.
Since $x\in f^{-1}(V)$, it must intersect $A$ at some point $x_{0}\in f^{-1}(V)\cap A$.
Thus $f(x_{0})\in V\cap f(A)$, giving us $y\in \overline{f(A)}$.
$2\implies3:$ Suppose 2. Let $B\subset Y$ be closed in $Y$.
Then $f(\overline{f^{-1}(B)})\subset \overline{f(f^{-1}(B))}\subset \overline{B}=B$ by 1.
Hence $\overline{f^{-1}(B)}=f^{-1}(f(\overline{f^{-1}(B)}))\subset f^{-1}(B)$.
It follows that $\overline{f^{-1}(B)}=f^{-1}(B)$, thus $f^{-1}(B)$ is closed in $X$.
$3\implies 1:$ Suppose 3. Let $V$ be an open set in $Y$.
Since $Y\setminus V$ is closed, we have $f^{-1}(Y\setminus V)$ is closed.
Now $X\setminus f^{-1}(V)=f^{-1}(Y)\setminus f^{-1}(V)=f^{-1}(Y\setminus V)$ is closed.
Hence $f^{-1}(V)$ is open, thus $f$ is continuous.
$1\implies 4:$ Suppose $f$ is cts. Let $x\in X$ and $V$ be a nbhd of $f(x)$.
Since $V$ is open, we have $f^{-1}(V)$ is open.
Thus $f^{-1}(f(V))\subset V$ is a nbhd of $x$.
$4\implies 1:$ Suppose $f$ is cts at $x$ for all $x\in X$.
Let $V$ be an open set in $Y$.
Then $\forall x\in f^{-1}(V)$, $\exists$ nbhd $U_{x}$ of $x$ s.t. $f(U_{x})\subset V$ by $4$.
Note that $U_{x}\subset f^{-1}(f(U_{x}))\subset f^{-1}(V)$ as a result.
Now $f^{-1}(V)\subset \displaystyle \bigcup_{x\in f^{-1}(V)}U_{x}\subset\bigcup_{x\in f^{-1}(V)}f^{-1}(V)\subset f^{-1} (V)$, hence equality holds in all inclusions.
Since each $U_{x}$ is open, we have $f^{-1}(V)$ is open.
