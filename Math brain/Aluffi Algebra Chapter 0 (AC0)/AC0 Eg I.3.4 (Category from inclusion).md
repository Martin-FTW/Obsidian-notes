Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Example I.3.4 (Category from inclusion)
Let $S$ be a set.
Define $\hat{S}$ by
- $\obj(\hat{S})=\power(S)$, the power set of $S$.
- $\forall A,B\subseteq S$, let $\hom_{\hat{S}}(A,B)=\set{(A,B)\given A\subseteq B}$.

Then $\hat{S}$ is a category.
#### Proof
This is a special case of [[AC0 Eg I.3.3 (Category from relation)]] by taking the inclusion partial order on the power set as the reflexive transitive relation.