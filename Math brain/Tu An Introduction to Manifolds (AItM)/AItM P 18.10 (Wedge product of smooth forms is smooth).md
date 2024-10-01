Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 18.10 (Wedge product of smooth forms is smooth)
Let $M$ be a manifold.
Let $\omega,\uptau\in \Omega ^*(M)$ be smooth forms on $M$.
Then $\omega \wedge\uptau\in \Omega ^*(M)$ is a smooth form on $M$.
#### Proof
Let $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart on $M$.
Write $\omega=\sum a_{I}dx^{I},\uptau=\sum b_{J}dx_{J}$ on $U$.
Then $\omega \wedge\uptau=\sum a_{I}b_{J}dx^{I}\wedge dx^{J}$.
View $I,J$ as sets.
If $I\cap J\neq \emptyset$, then $dx^{I}\wedge dx^{J}=0$.
Otherwise, reorder $I\cup J$ into increasing, then $\displaystyle \omega \wedge\uptau=\sum_{K}\left( \sum_{I\cap J=K}\pm a_{I}b_{J} \right)dx^{K}$