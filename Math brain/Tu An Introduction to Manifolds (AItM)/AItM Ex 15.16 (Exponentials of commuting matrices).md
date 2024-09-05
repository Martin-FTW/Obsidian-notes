Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exercise 15.16 (Exponentials of commuting matrices)
Let $A,B\in \mathcal{M}_{n}(\mathbb{R})\simeq \mathbb{R}^{n\times n}$ be commuting matrices.
Then $e^{A+B}=e^{A}e^{B}$
#### Proof
$\displaystyle e^{A}e^{B}=\sum \frac{A^{n}}{n!}\sum\frac{B^{n}}{n!}=\sum_{n}\sum_{k=0}^{n} \frac{A^{n-k}}{(n-k)!} \frac{B^{k}}{k!}=\sum \frac{(A+B)^{n}}{n!}=e^{A+B}$