Book: [[Tu An Introduction to Manifolds (AItM)]]
# Remark (Construction of bump functions)
Given $b>a>0,q\in \mathbb{R}^{n}$.
Domains of the following functions: $t\in \mathbb{R},x\in \mathbb{R}^{n}$
1. Let $f(t)=\begin{cases}e^{-1/t}&\text{if }t>0\\0&\text{if }t\leq 0\end{cases}$. Thus $f(t)\begin{cases}=0&\forall t\leq0\\=0&\forall t> 0\end{cases}$
2. Let $\displaystyle g(t)=\frac{f(t)}{f(t)+f(1-t)}$. Thus $g(t)\begin{cases}=0&\forall t\leq 0\\=1&\forall t\geq 1\end{cases}$
3. Let $\displaystyle h(t)=g\left( \frac{t-a^{2}}{b^{2}-a^{2}} \right)$. Thus $h(t)\begin{cases}=0&\forall t\leq a^{2}\\=1&\forall t\geq b^{2}\end{cases}$
4. Let $\displaystyle k(t)=h(t^{2})=g\left( \frac{t^{2}-a^{2}}{b^{2}-a^{2}} \right)$. Thus $k(t)\begin{cases}=0&\forall \abs{t}\leq a\\=1&\forall \abs{t}\geq b\end{cases}$
5. Let $\displaystyle \rho(t)=1-k(t)=1-g\left(\frac{t^{2}-a^{2}}{b^{2}-a^{2}} \right)$. Thus $k(t)\begin{cases}=1&\forall \abs{t}\leq a\\=0&\forall \abs{t}\geq b\end{cases}$ 
   Now $\rho$ a bump function at $0$ supported in $\clcl{-b}{b}$, i.e. $\supp\rho \subseteq \clcl{-b}{b}$
6. Let $\displaystyle \sigma(x)=\rho(\norm{x})=1-g\left( \frac{\norm{x}^{2}-a^{2}}{b^{2}-a^{2}} \right)$. Thus $\sigma(t)\begin{cases}=1&\forall \norm{x}\leq a\\=0&\forall \norm{x}>b\end{cases}$ 
   Now $\sigma$ is a bump function at $\vec{0}$ supported in $\overline{B}(\vec{0},b)$, i.e. $\supp \sigma \subseteq \overline{B}(\vec{0},b)$
7. Finally, $\sigma(x-q)$ is a bump function at $q$ supported in $\overline{B}(q,b)$.

Note that all functions above are composition of smooth functions and thus are smooth.