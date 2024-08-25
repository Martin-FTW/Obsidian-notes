Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Local base coordinates and fiber coordinates for smooth vector bundles)
Let $\pi:E\to M$ be a smooth vector bundle.
Let $(U,\psi)=(U,x^{1},\dots,x^{n})$ be a chart on $M$ and $\phi:E|_{U}\to U\times \mathbb{R}^{r}$ be a trivialization of $E$ over $U$, i.e. $\phi(e)=(\pi(e),c^{1}(e),\dots,c^{r}(e))$ for any $e\in E$.
Then $(\psi \times \mathbb{1})\circ \phi=(x^{1}\circ \pi,\dots,x^{n}\circ \pi,c^{1},\dots,c^{r}):E|_{U}\to \psi(U)\times \mathbb{R}^{r}$ is a diffeomorphism, thus $(E|_{U},(\psi \times \mathbb{1})\circ \phi)$ is a chart on $E$.
We call 
- $x^{1},\dots,x^{n}$ the base coordinates of $(E|_{U},(\psi \times \mathbb{1})\circ \phi)$
- $c^{1},\dots,c^{r}$ the fiber coordinates of $(E|_{U},(\psi \times \mathbb{1})\circ \phi)$

Note that the fiber coordinates depend only on the trivialization $\phi$ of the bundle $E|_{U}$ and not on the trivialization (coordinate map?) $\psi$ of the base $U$.