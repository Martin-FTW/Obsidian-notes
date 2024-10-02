Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 19.3 (Any antiderivation on the graded algebra of differential forms is a local operator)
Let $M$ be a manifold.
Let $D:\Omega^*(M)\to \Omega^*(M)$ be an antiderivation.
Then $D$ is a local operator.
#### Proof
Let $\omega\in \Omega^{k}(M)$ s.t. $\omega \equiv 0$ on some open set $U$.
Let $p\in U$.
Choose a smooth bump function $f$ at $p$ supported in $U$.
Then $f\equiv 1$ in a nbhd $V$ of $p$ in $U$.
Thus now we have $f\omega \equiv 0$ on $M$.
Now $0=D(0)=D(f\omega)=(Df)\wedge \omega+(-1)^{0}f\wedge(D\omega)$.
Evaluating both sides at $p$ gives $0=$