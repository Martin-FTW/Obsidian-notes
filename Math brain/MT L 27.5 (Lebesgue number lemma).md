Book: [[Munkres Topology (MT)]]
# Lemma 27.5 (Lebesgue number lemma)
Let $(X,d)$ be a metric space and $\mathscr{A}$ be an open covering of it.
Suppose $X$ is compact.
Then $\exists \delta>0:\forall B\subset X$ with $\diam B<\delta:\exists A\in \mathscr{A}:B\subset A$.
We call this $\delta$ a Lebesgue number for $\mathscr{A}$.
#### Proof
Case 1: Suppose $X\in \mathscr{A}$.
Then any $\delta>0$ is a Lebesgue number.
Case 2: Suppose $X\notin \mathscr{A}$.
Since $X$ is compact, $\exists$ finite subcover $\set{A_{i}}_{i=1}^{n}$.
Let $C_{i}= X\setminus A_{i}$ for each $i\in\ii{1}{n}$.
Let $f:X\to \mathbb{R}$ be $f(x)=\displaystyle \frac{1}{n}\sum_{i=1}^{n}d(x, C_{i})$ the arithmetic mean of the distances between the point $x\in X$ and each $C_{i}$.
Now let $x\in X$. Then $\exists i\in\ii{1}{n}:x\in A_{i}$.
Since $A_{i}$ is open $\exists \epsilon>0:B_{d}(x,\epsilon)\subset A_{i}$.
Then $d(x,C_{i})>\epsilon$, thus $f(x)= \frac{1}{n}\sum d(x,C_{j})\geq \frac{1}{n} d(x, C_{i})=\frac{\epsilon}{n}>0$.
It follows that $f>0$.
Since $f$ is continuous and $X$ is compact, $\exists \delta=\min f(X)>0$ by [[MT T 27.4 (Extreme value theorem)]].
Now let $B\subset X$ s.t. $\diam B<\delta$.
Take some $x_{0}\in B$, then $B\subset B_{d}(x_{0},\delta)$.
Now $\delta \leq f(x_{0})\leq \max \set{d(x_{0},C_{i})}_{i=1}^{n}=d(x_{0},C_{m})$ for some $m\in\ii{1}{n}$.
Hence $B_{d}(x_{0},\delta)\cap C_{m}=\emptyset$
Since $C_{m}=X\setminus A_{m}$, we have $B\subset B_{d}(x_{0},\delta)\subset A_{m}\in \mathscr{A}$. 