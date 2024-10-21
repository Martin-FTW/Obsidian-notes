Book: [[Folland Real Analysis (RAMT&TA)]]
# Definition (Polar decopmosition)
Let $(X,\mathcal{M})$ be a measurable space.
Let $f:X\to \overline{R}$ be a function.
Define $f^{+},f^{-}:X\to \mathbb{R}$ by $f^{+}(x)=\max \set{f(x),0}$ and $f^{-}(x)=\max \set{-f(x),0}$.
Now $f=f^{+}-f^{-}$, we call this the sign decomposition of $f$.
We call $f^{+}$ the positive part of $f$ and $f^{-}$ the negative part of $f$.
If $f$ is measurable we have $f^{+},f^{-}$ are measurable.

Now let $g:X \to \mathbb{C}$ be a function.
Define $\abs{g},\sgn g:X \to \mathbb{C}$ by $\abs{g}(z)=\abs{g(z)}$ and $(\sgn g)(z)= \sgn g(z)=\begin{cases}\frac{z}{\abs{z}}&z\neq 0\\0&z=0\end{cases}$ .
Now $g=(\sgn g)\abs{g}$, we call this the polar decomposition of $g$.
If $g$ is measurable then we have $\abs{g},\sgn g$ are measurable