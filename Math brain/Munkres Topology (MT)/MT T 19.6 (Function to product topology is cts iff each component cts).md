Book: [[Munkres Topology (MT)]]
# Theorem 19.6 (Function to product topology is cts iff each component cts)
Let $f_{\alpha}:A\to X_{\alpha}$ be functions $\forall \alpha\in J$.
Let $\prod X_{\alpha}$ have the product topology.
Let $f:A\to \prod X_{\alpha}$ be given by $f(a)=(f_{\alpha}(a))_{\alpha\in J}$.
Then $f$ is continuous iff $\forall \alpha\in J:f_{\alpha}$ is continuous.
#### Proof
$(\implies):$ Suppose $f$ is continuous.
Then $f_{\alpha}=\pi_{\alpha}\circ f$ is continuous for all $\alpha\in J$.
$(\impliedby):$ Suppose $f_{\alpha}$ is continuous for all $\alpha\in J$.
Let $\pi_{\alpha}^{-1}(U_{\alpha})$ be a subbasis element of $\prod X_{\alpha}$.
Then $f^{-1}(\pi_{\alpha}^{-1}(U_{\alpha}))=(\pi_{\alpha}\circ f)^{-1}(U_{\alpha})=f_{\alpha}^{-1}(U_{\alpha})$ is open in $A$.
It follows $f$ is continuous.