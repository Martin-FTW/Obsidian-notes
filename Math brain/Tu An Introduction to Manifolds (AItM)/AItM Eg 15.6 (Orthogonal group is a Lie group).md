Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 15.6 (Orthogonal group is a Lie group)
See [[AItM Eg 11.3 (Orthogonal group is a regular submanifold of general linear group)]], but we do not know what is the dimension of $O(n)$, thus we now try to use regular level set theorem to determine the codimension.
Let $f:\GL(n,\mathbb{R})\to \Sym_{n}$ be $f(A)=A\transpose A$.
Since $\Sym_{n}$ is a vector space, we have $T_{p}\Sym_{n}\simeq\Sym_{n}$ for all $p\in\Sym_{n}$.
Now $f_{*,A}:T_{A}(\GL(n,\mathbb{R}))\to T_{f(A)}\Sym_{n}\simeq\Sym_{n}$.
Note that $T_{A}(\GL(n,\mathbb{R}))\simeq T_{A}\mathbb{R}^{n\times n}\simeq \mathbb{R}^{n\times n}$.
Now $\forall X\in \mathbb{R}^{n\times n}$, $\exists$ curve $c(t)$ in $\GL(n,\mathbb{R})$ s.t. $c(0)=A,c'(0)=X$ by [[AItM P 8.16 (Existence of a curve with a given initial vector)]].
Thus $\displaystyle f_{*,A}(X)=\left.\frac{d}{dt}\right\vert_{0}f(c(t))=\left.\frac{d}{dt}\right\vert_{0}c(t)\transpose c(t)=(c'\transpose c+c\transpose c')(t)=X\transpose A+A\transpose X$ by [[AItM P 8.18 (Computing differential using curves)]].
Now let $B\in\Sym_{n}$. Take $X=\frac{1}{2}(A\transpose)^{-1}B$.
Then $f_{*,A}(X)=X\transpose A+A\transpose X=\frac{1}{2}(B\transpose+B)=B$.
It follows that $f_{*,A}(X)$ is surjective for all $A\in O(n)$.
Now $O(n)=f^{-1}(I)$ is a regular level set, thus $O(n)$ is a regular submanifold of $\GL(n,\mathbb{R})$ of codimension $\frac{n(n+1)}{2}$.
Hence $\dim O(n)=n^{2}-\frac{n(n+1)}{2}=\frac{n^{2}-n}{2}$.