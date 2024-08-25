Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Remark (Arc-length of curves on surface)
Let $S$ be a regular surface and $\alpha:I\to S$ be a regular curve on $S$.
Now the arc length $s$ of $\alpha$ is given by $\displaystyle s(t)=\int_{0}^{t}\norm{\alpha'(t)}\d t=\int_{0}^{t}\sqrt{ g(\alpha'(t),\alpha'(t)) }\d t$.
In particular, if $\alpha$ is contained in a coordinate nbhd with parametrization $\varphi(u,v)$, then in this neighbourhood we have $\displaystyle s(t)=\int_{0}^{t}\sqrt{ E(u')^{2}+2Fu'v'+G(v')^{2} }\d t$.
In view of this, we denote $ds^{2}=E\ du^{2}+2F\ dudv+G\ dv^{2}$, causing $\left( \dfrac{ds}{dt}  \right)^{2}=E\left( \dfrac{du}{dt}  \right)^{2}+2F\dfrac{du}{dt} \dfrac{dv}{dt} +G\left( \dfrac{dv}{dt}  \right)^{2}$.