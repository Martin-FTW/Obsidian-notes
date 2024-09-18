Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Exposition (Universal property of products)
Let $\mathsf{C}$ be a category and $A,B\in \obj \mathsf{C}$
Then their product $A\times B$ is universal w.r.t. of the property of mapping into $A,B$.
Translating the statement, we have 
- $\forall Z\in \obj(\mathsf{C}),f_{A}:Z\to A,f_{B}:Z\to B$, $\exists!\sigma:Z\to A\times B$ s.t. $f_{A}=\pi_{A}\circ \sigma,f_{B}=\pi_{B}\circ \sigma$.]

In categorical terms, we have
- $(\pi_{A},\pi_{B},A\times B)$ is final in the category $\mathsf{C}_{A,B}$ given in [[AC0 Eg I.3.9 (Slice 2)]]

In this case, we write $f_{A}\times f_{B}=(f_{A},f_{B})=\sigma$