# Fourier series
Let $f:\mathbb{R}\to \mathbb{C}$.
Suppose $f\in R_{2\pi}$, i.e. $f$ is $2\pi$-periodic Riemann-integrable.
Then $f\sim\displaystyle a_{0}+\sum_{n=1}^{\infty} (a_{n}\cos(nx)+b_{n}\sin(nx))=\sum_{n=-\infty}^{\infty}c_{n}e^{inx}$ is the fourier series of $f$, where 
$$\begin{array}{c|c}
\forall n\in \mathbb{Z}_{>0}:&\forall n\in \mathbb{Z}:\\\hline
\begin{array}{l}
\displaystyle a_{0}=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(t)\d t & \\
\displaystyle a_{n}=\frac{1}{\pi}\int_{-\pi}^{\pi}f(t)\cos(nt)\d t \\
\displaystyle b_{n}=\frac{1}{\pi}\int_{-\pi}^{\pi}f(t)\sin(nt)\d t
\end{array}&\begin{array}{l}\displaystyle
c_{n}=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(t)e^{-int}\d t \\
\phantom{c_{n}}=\begin{cases}
\dfrac{a_{n}-ib_{n}}{2} &\text{if }n>0\\
a_{0}&\text{if }n=0\\
\dfrac{a_{-n}+ib_{-n}}{2} &\text{if }n<0
\end{cases}
\end{array}\end{array}$$
Define the partial sum $\displaystyle (S_{n}f)(x)=a_{0}+\sum_{k=1}^{n} (a_{k}\cos(kx)+b_{k}\sin(kx))=\sum_{k=-n}^{n}c_{k}e^{ikx}$
Denote $\mathcal{C}=\set{(c_{n})_{n\in \mathbb{Z}}\subseteq \mathbb{C}\given c_{n}\to 0\text{ as }n\to \pm \infty}$ and let the fourier map $\Phi:R_{2\pi}\to \mathcal{C},\Phi(f)=(\hat{f}(n))=(c_{n})$ 
Note that $\Phi$ is linear.
## Riemann-Lebesgue lemma
$\displaystyle\forall f\in R\clcl{a}{b}:$
$\displaystyle\lim\left( \int_{a}^{b}f(t)\cos(nt)\d t \right)=0=\lim\left( \int_{a}^{b}f(t)\sin(nt)\d t \right)$
## Uniqueness
If $f\in R_{2\pi}:\Phi(f)=\Phi(g)\iff f=g$ a.e.
If $f\in C\clcl{a-\pi}{a+\pi}\cap R_{2\pi}:\Phi(f)=\Phi(g)\iff f=g$ 
## The fourier map
Suppose $f,f',\dots,f^{(k)}\in R_{2\pi}$.
For any $a\in \mathbb{R},$ let $g\in R_{2\pi}$ be $g(x)=f(x-a)$.
Then
- $\Phi(f^{(k)})=(in)^{k}\Phi(f)$, or $\forall n\in \mathbb{Z}:\widehat{f^{(k)}}(n)=(in)^{k}\hat{f}(n)$
- $\Phi(g)=e^{-ina}\Phi(g)$, or $\forall n\in \mathbb{Z}:\hat{g}(n)=e^{-ina}\hat{f}(n)$.
## Dirichlet kernel
Let $D_{n}:\mathbb{R}\to \mathbb{C}$ be the Dirichlet kernel $$\begin{align}
D_{n}(x)&=\begin{cases}\displaystyle \frac{\sin\left( \left( n+\frac{1}{2} \right)x \right)}{2\pi \sin\left( \frac{1}{2}x \right)}&\text{if }x\neq 0\\\dfrac{2n+1}{2\pi}&\text{if }x=0\end{cases} \\
&=\frac{1}{2\pi}\sum_{k=-n}^{n}e^{ikx} \\
&=\frac{1}{2\pi}\left( 1+2\sum_{k=1}^{n}\cos(kx) \right)
\end{align}$$
Then $\forall n\in \mathbb{Z}_{>0}$, we have
- $\displaystyle (S_{n}f)(x)=\int_{-\pi}^{\pi}D_{n}(t)f(x+t)\d t$
- $D_{n}$ is even, continuous, $2\pi$-periodic 
- $D_{n}$ has zeroes at $\displaystyle \frac{2k\pi}{2n+1},k\in\ii{{-n}}{n}$ and maximum at $\displaystyle D_{n}(0)=\frac{2n+1}{2\pi}$
- $\displaystyle\int_{-\pi}^{\pi}D_{n}=1$ and $\displaystyle \forall \delta>0:\lim\left( \int_{0}^{\delta}\abs{D_{n}} \right)=\infty$
## Convergence of fourier
Let $f\in R_{2\pi}\clcl{-\pi}{\pi}$ and $x\in \clcl{-\pi}{\pi}$. 
Suppose $\displaystyle f(x^{+})\coloneqq\lim_{y\to x^{+}}f(y),f(x^{-})\coloneqq\lim_{y\to x^{-}}f(y)$ exist and
- $\exists \delta,L>0:\begin{cases}\forall y\in \opop{-\pi}{x}:\abs{f(y)-f(x^{-})}\leq L(x-y)\\\forall y\in \opop{x}{\pi}:\abs{f(y)-f(x^{+})}\leq L(y-x)\end{cases}$
Then $\displaystyle \lim(S_{n}f(x))=\frac{f(x^{+})+f(x^{-})}{2}$
In particular, 
- If $f$ is lipschitz at $x$, then $\lim(S_{n}f(x))=f(x)$.
- If $f$ is uniformly lipschitz, then $S_{n}f\to f$ unfiromly on $\mathbb{R}$.