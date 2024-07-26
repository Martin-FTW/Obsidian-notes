Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 6.10 (Any coordinate map is a diffeomorphism)
Let $M$ be a manifold of dimension $n$.
Let $(U,\phi)$ be a chart on $M$.
Then $\phi:U\to \phi(U)$ is a diffeomorphism.
#### Proof
Since $\phi$ is a homeomorphism, it suffices to check $C^{\infty}$ for $\phi$ and $\phi ^{-1}$.
Let $\mathfrak{U}=\set{(U,\phi)},\mathfrak{V}=\set{\phi(U),\id_{\phi(U)}}$ be atlases for $M,\phi(U)$ respectively.
Then we have $\id_{\phi(U)}\circ \phi \circ \phi ^{-1}:\phi(U)\to \phi(U)$ is $C^{\infty}$ since it is the identity map.
By [[AItM P 6.8 (Characterization of smooth maps between manifolds)]], $\phi$ is $C^{\infty}$.
Similarly, $\phi \circ \phi ^{-1}\circ \id_{\phi(U)}$ is the identity map, thus is $C^{\infty}$.