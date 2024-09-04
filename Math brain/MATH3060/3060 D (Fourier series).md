Book: [[MATH3060]]
# Definition (Fourier series)
Let $f:\clcl{-\pi}{\pi}\to \mathbb{R}$ be a $2\pi$-periodic Riemann-integrable function.
For all $n\in \mathbb{Z}_{>0}$, let $$\begin{align}
a_{0}&=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(t)\d t \\
a_{n}&=\frac{1}{\pi}\int_{-\pi}^{\pi}f(t)\cos(nt)\d t \\
b_{n}&=\frac{1}{\pi}\int_{-\pi}^{\pi}f(t)\sin(nt)\d t
\end{align}$$
We call $\displaystyle a_{0}+\sum_{n=1}^{\infty} (a_{n}\cos(nx)+b_{n}\sin(nx))$ the fourier series of $f$.