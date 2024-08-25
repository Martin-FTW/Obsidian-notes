Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Example I.3.3 (Category from relation)
Let $S$ be a set and $\sim$ be a relation on $S$.
Suppose $\sim$ is reflexive and transitive.
Define $\mathsf{C}$ by the following:
- $\obj \mathsf{C}=S$
- $\forall a,b\in S$, let $\hom(a,b)=\set{(a,b)\given a\sim b}$.

Then $\mathsf{C}$ is a category.
#### Proof
Identity: $1_{a}=(a,a)\in \hom(a,a)$ which exists by reflexivity.
Composition: 
Let $a,b,c\in S$. Let $f\in \hom(a,b),g\in \hom(b,c)$.
Then $f=(a,b)$ and $g=(b,c)$, thus $a\sim b$ and $b\sim c$.
Since $\sim$ is transitive, we have $a\sim c$.
Define $gf=(a,c)\in \hom(a,c)$. Thus composition is well-defined.
Let $f\in \hom(a,b),g\in \hom(b,c),h\in \hom(c,d)$.
Then $f=(a,b),g=(b,c),h=(c,d)$, thus $hg=(b,d), gf=(a,c)$.
Hence $(hg)f=(a,d)=h(gf)$.