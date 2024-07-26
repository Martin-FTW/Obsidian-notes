Book: [[Munkres Topology (MT)]]
# Theorem 27.1 (Every closed interval of ordered sets with lub property is compact)
Let $X$ be a simply ordered set having the least upper bound property.
Then every closed interval in $X$ with the order topology is compact. 
That is, for any $a<b$ and open covering $\mathscr{A}$ of $\clcl{a}{b}$, there is a finite subcover.
## Lemma
For any $x\in[a,b):\exists y_{x}\in(x,b]:[x,y]$ can be covered by $\leq2$ elements of $\mathscr{A}$

#### Proof
For the lemma:
Case 1: If $x$ has an immediate successor $y$, Then $[x,y]=\set{x,y}$, thus it can be covered by at most two elements that contain each $x,y$.
Case 2: If $x$ has no immediate successor, choose some $A\in \mathscr{A}$ that contains $x$.
Since $A$ is open and $x\neq b$, $\exists c\in(x,b]$ s.t. $A\supset [x,c)$.
Now since $x$ has no immediate successor, $\exists y\in(x,c)$.
Now $[x,y]$ is covered by the single $A\in \mathscr{A}$.

Let $C=\set{y\in(a,b]\given \exists \text{ finite }\set{A_{i}}_{i=1}^{n}\subset\mathscr{A}:[a,y]\subset \bigcup_{i}A_{i}}$.
Now by lemma, we have $y_{a}\in C$, thus $C\neq \emptyset$.
Take $c=\sup C$, thus $a<c\leq b$.
Let $A\in \mathscr{A}$ be containing $c$.
Since $A$ is open, $\exists d\in[a,c):(d,c]\subset A$.
Suppose on the contrary that $c\notin C$.
Then $\exists z\in C:z\in(d,c)$ by definition of sup.
Now $[a,z]$ can be covered by $\set{A_{i}}_{i=1}^{n}\subset \mathscr{A}$ by definition of $C$.
Hence $A\cup \bigcup_{i}A_{i}\supset[a,z]\cup(d,c]\supset[a,z]\cup[z,c]\supset[a,c]$.
Now $\set{A}\cup \set{A_{i}}$ is a finite cover, contradicting $c\notin C$.

Finally, suppose on the contrary that $c\neq b$, then $c<b$.
Now by lemma, we have $y_{c}\in(c,b]$ s.t. the interval $[c,y_{c}]$ can be covered by finitely many elements of $\mathscr{A}$.
However, since $c\in C$, $[a,c]$ can also be covered by finitely many elements of $\mathscr{A}$.
Therefore, $[a,y]=[a,c]\cup[c,y]$ can be covered by finitely many elements of $\mathscr{A}$.
Hence, $y\in C$, contradicting that $c$ is an upper bound of $C$.