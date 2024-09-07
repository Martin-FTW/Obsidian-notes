Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 16.4 (Tangent space to orthogonal group at identity)
Let $X\in T_{I}O(n)$.
Choose a curve $c(t)$ in $O(n)$ s.t. $c(0)=I,c'(0)=X$.
By definition of $O(n)$, we have $c(t)\transpose c(t)=I$ for all $t$.
Differentiating both sides gives $c'(t)\transpose c(t)+c(t)\transpose c'(t)=0$.
Evaluating at $0$ gives $X\transpose+X=0$, thus $X$ is skew-symmetric.
Now $T_{I}O(n)\subseteq \Skew_{n}$.
Since $\dim\Skew_{n}=\frac{n(n-1)}{2}=\dim O(n)=\dim T_{I}O(n)$ by [[AItM Eg 15.6 (Orthogonal group is a Lie group)]], the spaces must be equal