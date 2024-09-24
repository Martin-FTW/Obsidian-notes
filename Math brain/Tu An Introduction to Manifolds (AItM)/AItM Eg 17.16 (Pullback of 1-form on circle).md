Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 17.16 (Pullback of 1-form on circle)
Consider the immersed submanifold $i:\mathbb{S}^{1}\to \mathbb{R}^{2}$.
Let $h:\mathbb{R}\to \mathbb{S}^{1}$ be $h(t)=(x,y)=(\cos t,\sin t)$.
Let $\omega=-ydx+xdy$ be a $1$-form on $\mathbb{S}^{1}$.
Compute $h\pullback \omega$.
#### Proof
$h\pullback \omega=h\pullback(-ydx+xdy)$
$=(-y\circ h) h\pullback dx+(x\circ h)h\pullback dy$
$=(-\sin t)d(h\pullback x)+(\cos t)d(h\pullback y)$
$=-(\sin t)d(\cos t)+(\cos t)d(\sin t)$
$=\sin ^{2}tdt+\cos ^{2}tdt$
$=dt$.