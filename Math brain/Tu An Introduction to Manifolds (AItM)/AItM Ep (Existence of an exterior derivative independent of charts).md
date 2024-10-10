Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exposition (Existence of an exterior derivative independent of charts)
Let $M$ be a manifold and $\omega$ be a $k$-form on $M$.
Let $p\in M$ and $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart about $p$.
Suppose $\omega=\sum a_{I}dx^{I}$ on $U$.
Define $(d\omega)_{p}=(d_{U}\omega)_{p}$. In order to be well-defined, $(d_{U}\omega)_{p}$ needs to be independent of the chart $U$ about $p$.
Let $(\tilde{U},\tilde{\phi})=(\tilde{U},\tilde{x}^{1},\dots,\tilde{x}^{n})$ be another chart about $p$ and $\omega=\sum \tilde{a}_{J}d\tilde{x}^{J}$ on $\tilde{U}$.
Then on $U\cap \tilde{U}$, we have $\sum a_{I}dx^{I}=\sum \tilde{a}_{J}dx^{J}$.
We also have another unique exterior derivative $d_{U\cap \tilde{U}}:\Omega^*(U\cap \tilde{U})\to \Omega^*(U\cap \tilde{U})$ by [[AItM Ep (Existence of exterior derivative locally on coordinate charts)]].
Now we have $d_{U\cap \tilde{U}}(\sum a_{I}dx^{I})=d_{U\cap \tilde{U}}(\sum \tilde{a}_{J}dx^{J})$
$\implies$