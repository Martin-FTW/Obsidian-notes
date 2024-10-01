Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exposition (Differential forms on a circle)
Let $h:\mathbb{R}\to \mathbb{S}^{1}$ be $h(t)=(\cos t,\sin t)$.
Since $\dot{h}(t)=(-\sin t,\cos t)$ is nowhere vanishing, we have $h$ is a submersion.
Thus $h\pullback:\Omega ^*(\mathbb{S}^{1})\to \Omega ^*(\mathbb{R})$ is injective.
Let $\omega=-ydx+xdy$ be the nowhere-vanishing form on $\mathbb{S}^{1}$ from [[AItM Eg 17.15 (1-form on circle)]].
By the nowhere-vanishing property, $\set{\omega}$ is a frame for $T^*\mathbb{S}^{1}$.
Thus $\forall$ $1$-form $\alpha$ on $\mathbb{S}^{1}$, we can write $\alpha=f\omega$ for some $f:\mathbb{S}^{1}\to \mathbb{R}$.
Note that $f$ is smooth by [[AItM P 12.12 (Characterization of smooth sections)]]
Thus $\bar{f}=h\pullback f$ is smooth.
From [[AItM Eg 17.16 (Pullback of 1-form on circle)]], we have $h\pullback \omega=dt$.
Hence $h\pullback \alpha=(h\pullback f)(h\pullback \omega)$ by [[AItM P 18.11 (Pullback of wedge product)]].