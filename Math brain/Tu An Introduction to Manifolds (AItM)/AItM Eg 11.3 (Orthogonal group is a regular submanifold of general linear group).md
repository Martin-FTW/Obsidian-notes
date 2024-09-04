Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 11.3 (Orthogonal group is a regular submanifold of general linear group)
Let $f:\GL(n,\mathbb{R})\to\GL(n,\mathbb{R})$ be $f(A)=A\transpose A$.
Then $O(n)=f^{-1}(I)$. It suffices to show $f$ has constant rank:
Let $A,B\in\GL(n,\mathbb{R})$. Then $\exists!C=A^{-1}B\in\GL(n,\mathbb{R})$ s.t. $B=AC$.
Now $f(AC)=(AC)\transpose AC=C\transpose A\transpose AC=C\transpose f(A)C$, thus $f\circ r_{C}=\ell_{C\transpose}\circ r_{C}\circ f$.
Now $f_{*,AC}\circ(r_{C})_{*,A}=(f\circ r_{C})_{*,A}=(\ell_{C\transpose}\circ r_{C}\circ f)_{*,A}=(\ell_{c\transpose})_{*,A\transpose AC}\circ(r_{C})_{*,AC}\circ f_{*,A}$.
Since $\ell_{C}$ and $r_{C}$ are diffeomorphisms, their differentials are isomorphisms, thus preserve the rank in the composition.
Hence $\rank f_{*,B}=\rank f_{*,AC}=\rank f_{*,A}$.
It follows that $f$ has constant rank on $\GL(n,\mathbb{R})$.
By [[AItM T 11.2 (Constant-rank level set theorem)]], $O(n)$is a regular submanifold of $\GL(n,\mathbb{R})$