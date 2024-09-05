Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 15.17 (Derivative of matrix exponential)
Let $X\in \mathbb{R}^{n\times n}$.
Then $\displaystyle\frac{d}{dt}e^{tX}=Xe^{tX}=e^{tX}X$.
#### Proof
By [[ItRA T 9.4.4 (term by term diff)]], we have $\displaystyle \frac{d}{dt}e^{tX}=\sum \frac{1}{k!}\frac{d}{dt}(tX)^{k}=\sum \frac{1}{(k+1)!}X^{k+1}(k+1)t ^{k}=\sum \frac{X^{k+1}}{k!}t^{k}$.
Now by factoring out $X$ to the left or right by [[AItM P 15.14 (Distributivity of convergent series on normed algebra)]] gives the claim.