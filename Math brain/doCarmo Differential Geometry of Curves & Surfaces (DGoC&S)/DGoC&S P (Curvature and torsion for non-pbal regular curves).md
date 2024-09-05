Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition (Curvature and torsion for non-pbal regular curves)
Let $\alpha:I\to \mathbb{R}^{3}$ be a regular curve.
Define the curvature $k(t)$ and torsion $\uptau(t)$ by that of the arc-length reparameterization $\beta$ of $\alpha(I)$.
Then as functions of $t\in I$, we have
- $k=\dfrac{\norm{\alpha''\times \alpha'}}{\norm{\alpha'}^{3}}$
- $\uptau=\dfrac{\innerp{\alpha'''}{\alpha'\times \alpha''}{}}{\norm{\alpha'\times \alpha''}^{2}}$
#### Proof
Let $s:J\to I$ be such that $\frac{ds}{dt}=\norm{\gamma'(t)}$, that is $\gamma \circ s ^{-1}$ is the arclength reparamerization of $\gamma$.
Then $\displaystyle \gamma'(t)=\frac{d\gamma}{ds}\frac{ds}{dt}=T(t)\norm{\gamma'(t)}$ and $\displaystyle T'(t)=\frac{dT}{ds}\frac{ds}{dt}=\norm{\gamma'(t)}\kappa(t)N(t)$
Now $\gamma''=\norm{\gamma'}'T+\norm{\gamma}T'=\norm{\gamma'}'T+\norm{\gamma'}^{2}\kappa N$
Thus $\gamma'''=\norm{\gamma'}''T+\norm{\gamma'}'T'+(\norm{\gamma'}^{2}\kappa)'N+\norm{\gamma'}^{2}\kappa N'$
Since $N'=-\kappa T+\uptau B$, we have $\gamma'''=(*)T+(*)N+\kappa\uptau B$.
Hence $\norm{\gamma'\times \gamma''}$