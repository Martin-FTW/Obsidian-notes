Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Rigid motion, translation)
Let $V$ be a real inner product space.
Let $d$ be the induced metric from the induced norm from $V$.
Let $f,g:V\to V$ be a function.
We call $g$ a translation if $\exists v_{0}\in V:\forall x\in V:g(x)=x+v_{0}$.
We call $f$ a rigid motion if $f$ is an isometry of $(V,d)$, i.e. $\norm{f(x)-f(y)}=\norm{x-y}$ for all $x,y\in V$.
By [[LA T 6.22 (Rigid motions uniquely decomposes into orthogonal then translation)]], $\exists!$ orthogonal operator $T$ on $V$ and translation $g$ s.t. $f=g\circ T$.
We call $f$
- orientation-preserving if $\det T>0$
- orientation-reversing if $\det T<0$