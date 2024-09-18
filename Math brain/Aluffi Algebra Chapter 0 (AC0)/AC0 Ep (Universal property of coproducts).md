Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Exposition (Universal property of coproducts)
Let $\mathsf{C}$ be a category and $A,B\in \obj \mathsf{C}$
Then their coproduct $A\coprod B$ is universal w.r.t. of the property of mapping from $A,B$.
Translating the statement, we have 
- $\forall Z\in \obj(\mathsf{C}),f_{A}:A\to Z,f_{B}:B\to Z$, $\exists!\sigma:A\coprod B\to Z$ s.t. $f_{A}=i_{A}\circ \sigma,f_{B}=i_{B}\circ \sigma$.

In categorical terms, we have
- $(\pi_{A},\pi_{B},A\times B)$ is final in the category $\mathsf{C}^{A,B}$ given in [[AC0 Eg I.3.9 (Slice 2)]]

In this case, we write $f_{A}\coprod f_{B}=\sigma$