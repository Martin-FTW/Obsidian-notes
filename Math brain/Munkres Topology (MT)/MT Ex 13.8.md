Book: [[Munkres Topology (MT)]]
# Exercise 13.8
Show that $\mathscr{B}=\set{(a,b)\given a,b\in \mathbb{Q},a<b}$ is a basis that generates the standard topology on $\mathbb{R}$.

Show that $\mathscr{C}=\set{[a,b)\given a,b\in \mathbb{Q},a<b}$ is a basis that generates a topology different from the lower limit topology on $\mathbb{R}$.

#### Proof
Let $U$ be open and $x\in U$. Then $x\in (a,b)\subset U$ for some $a<x<b$.
Since $\mathbb{Q}$ is dense, $\exists r_{1},r_{2}\in \mathbb{Q}$ s.t. $r_{1}\in(a,x)$ and $r_{2}\in(x,b)$.
Now $x\in(r_{1},r_{2})\subset U$ and $(r_{1},r_{2})\in \mathscr{B}$.
Hence $\mathscr{B}$ is a basis for the standard topology on $\mathbb{R}$.

Note that $[\sqrt{ 2 },2)$ is open in the lower limit topology.
Suppose $\mathscr{C}$ generated the lower limit topology.
Then $\exists a,b\in \mathbb{Q}$ with $a<b$ s.t. $\sqrt{ 2 }\in [a,b)\subset[\sqrt{ 2 },2)$.
Now $a\leq\sqrt{ 2 }<b$ and $\sqrt{ 2 }\leq a<b\leq{2}$.
In particular, $\sqrt{ 2 }\leq a\leq \sqrt{ 2 }$, thus $a=\sqrt{ 2 }\in \mathbb{Q}$. Contradiction.