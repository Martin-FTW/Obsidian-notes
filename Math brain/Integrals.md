# Integrals
## Riemann integral

## Differential forms
### General
Let $M$ be a $k$-dimensional Parameterized manifold in $\mathbb{R}^{n}$ with parameterization $g:U\to M$.
Let $\omega\in\Omega^{k}(M)$ be a $k$-Differential form.
Then we define the integral of $\omega$ on $M$ as $$\int_{M}\omega=\int_{U}g^{*}\omega$$
### Top degree (k=n)
Let $\Omega\in\power(\mathbb{R}^{n})$.
Let $\omega=f(x)dx_{1}\wedge\cdots\wedge dx_{n}\in\Omega^{n}(\Omega)$ be an $n$-Differential form.
We define the integral of $\omega$ on $\Omega$ as $$\int_{\Omega}\omega=\int_{\Omega}f\d V$$
### Volume form ...?
Let $M$ be a $k$-dimensional Parameterized manifold in $\mathbb{R}^{n}$ with parameterization $g:U\to M$.
Let $f:M\to \mathbb{R}$ be a continuous Function.
We define the integral of $f$ as $$\int_{M}f\d\sigma=\int_{U}f\circ g\sqrt{ \det(g_{i,j}) }\d V$$
### Line integral (k=1)
Let $U\in\power(\mathbb{R}^{n})$ be a set.
Let $C\in\power(U)$ be a curve.
Let $\vec{\gamma}:\clcl{a}{b}\to C$ be a regular bijective parameterization of $C=\gamma(\clcl{a}{b})$.
#### Scalar field
Let $f:U\to \mathbb{R}$.
The integral
$$
\int_{C}f\,\d s\coloneqq\int_{a}^{b}f\circ\vec{\gamma}(t)\cdot \abs{\vec{\gamma}'(t)}\,\d t
$$
is called the line integral of $f$ along $C$ (with the parameterization $\vec{\gamma}$).
Note that this is well-defined by Line integral along any curve is independent of choice of parameterization.
If $C$ is a Closed curve, then we denote the closed integral as $\displaystyle\oint_{C} f\,\d s\coloneqq\int_{C}f\,\d s$
#### Vector field
Let $F:U\to \mathbb{R}^{n}$.
The integral
$$\int_{C} F\cdot\,\d \vec{r}\coloneqq\int_{a}^{b} F\circ \vec{\gamma}(t)\cdot \vec{\gamma}'(t)\,\d t$$is called the line integral of $F$ along $C$ (with the parameterization $\vec{\gamma}$).
Note that this is well-defined by Line integral along any curve is independent of choice of parameterization.
If $C$ is a Closed curve, then we denote the closed integral as $\displaystyle\oint_{C} F\ddr\coloneqq\int_{C}F\ddr$

### Surface integral (k=2)
Let $U\in \power(\mathbb{R}^{2})$
Let $S$ be a parametric surface.
Let $g:U\to S$ be a regular bijective parameterization of $S$.
#### Scalar field
Let $f:S\to \mathbb{R}$ be a continuous Scalar field.
The integral $$\int_{S} f \, \d \sigma=\iint_{U}(f\circ g)\cdot \norm*{\frac{ \partial g }{ \partial u } \times \frac{ \partial g }{ \partial v } } \,\d A$$
is called the surface integral.
#### Vector field
Let $F:S\to \mathbb{R}^{3}$ be a continuous Vector field.
The integral $$\int_{S} F\cdot\d\sigma=\int_{S}F\cdot \vec{n}\,\d\sigma=\iint_{U}(F\circ g)\cdot \left( \frac{ \partial g }{ \partial u } \times \frac{ \partial g }{ \partial v } \right)\,\d A$$
##