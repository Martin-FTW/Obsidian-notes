# ODE techniques
General form: $F(x,y,y',\dots,y^{(n)})=0$
To solve: $y(x;c_{1},\dots,c_{n})$
## First order $n=1$
### Separable $\displaystyle y'=\frac{g(x)}{h(y)}\iff F(x,y,y')=h(y)y'-g(x)$
==Solve:== $\displaystyle \implies \int h(y)\d y=\int g(x)\d x\implies H(y)=G(x)+C$
Be careful when $h(y)=0$, split cases
### Linear $y'+p(x)y=q(x)\iff F(x,y,y')=Ly+q(x)$
Note that if $p\equiv 0$ then the ODE is separable
Otherwise, take one $\displaystyle \mu(x)=\exp\left( \int p(x)\d x \right)$.
==Solve: ==$\implies\displaystyle (\mu y)'= \mu q\implies y=\frac{1}{\mu}\int(\mu q)=\frac{Q(x)+C}{\mu(x)}$
### Exact $M(x,y)+N(x,y)y'=0$, $(M,N)=\nabla \Psi$
If $C^{1}$ and $\Omega$ convex: $(M,N)=\nabla \Psi \iff M_{y}=N_{x}$
Since $\Psi_{x}=M$ we have $\displaystyle \Psi(x,y)=\int M(x,y)\d x=P(x,y)+h(y)$.
SInce $\Psi_{y}=N$ we have $h'(y)=N(x,y)-P_{y}(x,y)$ which is independent of $x$.
Take one $\displaystyle h(y)=\int (N-P_{y})=Q(y)$.
==Solve:== $\implies \Psi(x,y)=C\iff P(x,y)+Q(y)=C$ (implicit)
#### Almost exact $(\mu(x),\mu(x)N)=\nabla \Psi$
$\displaystyle (\mu(x),\mu(x)N)=\nabla \Psi \iff \frac{M_{y}-N_{x}}{N}$ only depends on $x$
$\displaystyle \implies \text{Take one } \mu(x)=\exp\left( \int \frac{M_{y}-N_{x}}{N} \right)$
#### Almost exact $(\mu(y)M),\mu(y)N)=\nabla \Psi$
$\displaystyle (\mu(y),\mu(y)N)=\nabla \Psi \iff \frac{N_{x}-M_{y}}{M}$ only depends on $y$
$\displaystyle \implies \text{Take one } \mu(y)=\exp\left( \int \frac{N_{x}-M_{y}}{M} \right)$
### Linear sub $y'=f(ax+by+c)$
Let $v=ax+by+c$, i.e. $v(x)=ax+by(x)+c$.
Then $\displaystyle v'=a+by'=a+bf(v)\implies \frac{v'}{a+bf(v)}=1$ separable
==Solve:== $\displaystyle y=\frac{v(x)-ax-c}{b}$
### Homogeneous $\displaystyle y'=\varphi\left( \frac{y}{x} \right)$
Let $\displaystyle v=\frac{y}{x}$, i.e. $\displaystyle v(x)=\frac{y(x)}{x}$.
Then $\displaystyle \varphi(v)=y'=(xv)'=v+xv'\implies \frac{v'}{\varphi(v)-v}=\frac{1}{x}$ separable
==Solve:== $y=xv(x)$
### Bernoulli $y'+py=qy^{n}$, $n>1$
Let $\displaystyle z=y^{1-n}=\frac{1}{y^{n-1}}$. 
Then we have the first order linear ODE in $z$: $z'=(1-n)y^{-n}y'=(1-n)y^{-n}(-py+qy^{n})=-(1-n)pz+(1-n)q$
==Solve:== $\displaystyle y=\pm \sqrt[n-1]{ \frac{1}z }$ depending on odd/even./
## Second order linear
	It suffices to find fundamental set by Wronskian
### Abel $(y_{1}\implies y_{2})$
Given $y_{1}$ solves $y''+py'+qy=0$, find $y_{2}$:
Take one $y_{1}y_{2}'-y_{1}'y_{2}=W(y_{1},y_{2})(t)=C_{0}e^{-\int p}\implies$ first order linear ODE 
### Reduction of order $(y_{1}\implies y_{2})$
Given $y_{1}$ solves $y''+py'+qy=0$, find $y_{2}$:
Let $y_{2}=v(t)y_{1}(t)$
### Constant coef $(\implies y_{1},y_{2})$
Consider $L(y)=ay''+by'+cy=0$
Characteristic equation $ar^{2}+br+c=0$

| $\Delta$ |          $r_{1},r_{2}$          |                    $y_{1},y_{2}$                    |                              $y$                              |
| :------: | :-----------------------------: | :-------------------------------------------------: | :-----------------------------------------------------------: |
|   $>0$   | $r_{1}\neq r_{2}\in \mathbb{R}$ |               $e^{r_{1}t},e^{r_{2}t}$               |               $C_{1}e^{r_{1}t}+C_{2}e^{r_{2}t}$               |
|   $=0$   |   $r_{1}=r_{2}\in \mathbb{R}$   |              $e^{r_{1}t},te^{r_{1}t}$               |              $C_{1}e^{r_{1}t}+C_{2}te^{r_{1}t}$               |
|   $<0$   |    $r_{1,2}=\lambda\pm i\mu$    | $e^{\lambda t}\cos(\mu t),e^{\lambda t}\sin(\mu t)$ | $C_{1}e^{\lambda t}\cos(\mu t)+C_{2}e^{\lambda t}\sin(\mu t)$ |
### Method of undetermined coef $(\implies Y)$
Consider $L(y)=ay''+by'+cy=0$.
Characteristic equation $ar^{2}+br+c=0$, $m(r)\coloneqq$ multiplicity of $r$

| $g(t)$                                                                       | $Y(t)$                                                                           |
| :--------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| $P_{n}(t)$                                                                   | $t ^{m(0)}Q_{n}(t)$                                                              |
| $P_{n}(t)e^{\alpha t}$                                                       | $t ^{m(\alpha)}Q_{n}(t)e^{\alpha t}$                                             |
| $P_{n}(t)e^{\alpha t}\cos (\beta t)$<br>$P_{n}(t)e^{\alpha t}\sin (\beta t)$ | $t ^{m(\alpha+i\beta)}e^{\alpha t}(Q_{n}(t)\cos(\beta t)+R_{n}(t)\sin(\beta t))$ |

### Variation of parameters $(\implies Y)$
Consider $y''+p(t)y'+q(t)y=g(t)$.
Let $y_{1},y_{2}$ form a fundamental set of solutions to $y''+py'+qy=0$.
==Solve==: Let $Y=u_{1}y_{1}+u_{2}y_{2}$, i.e. $Y(t)=u_{1}(t)y_{1}(t)+u_{2}(t)y_{2}(t)$.
$\displaystyle\implies \begin{cases}u_{1}'y_{1}+u_{2}'y_{2}=0\\u_{1}'y_{1}'+u_{2}'y_{2}'=g\end{cases}\implies \begin{bmatrix}y_{1}&y_{2}\\y_{1}'&y_{2}'\end{bmatrix}\begin{bmatrix}u_{1}'\\u_{2}'\end{bmatrix}=\begin{bmatrix}0\\g\end{bmatrix}$
Cramer's rule $\displaystyle \implies u_{1}'(t)=\frac{-y_{2}(t)g(t)}{W(y_{1},y_{2})(t)},u_{2}'(t)=\frac{y_{1}(t)g(t)}{W(y_{1},y_{2})(t)}$
## Higher order linear
### Reduction of order $(y_{1}\implies y_{2})$
Given $y_{1}$ solves $y''+py'+qy=0$, find $y_{2}$:
Let $y_{2}=v(t)y_{1}(t)$
### Constant coef $(\implies y_{k})$
Consider $\displaystyle L(y)=\sum_{k=0}^{n} a_{k}y^{(k)}=0$
Characteristic equation: $\displaystyle\sum_{k=0}^{n}a_{k}r^{k}=\prod_{j=1}^{m}(r-r_{j})^{m_{j}}=0$, $r_{j}$ all distinct

|        $r_{j}$        |                                                                                              $y_{k}$                                                                                               |
| :-------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| $r_{j}\in \mathbb{R}$ |                                                                        $e^{r_{j}t},te^{r_{j}t},\dots,t^{m_{j}-1}e^{r_{j}t}$                                                                        |
| $r_{j}=\lambda+i\mu$  | $e^{\lambda t}\cos(\mu t),te^{\lambda t}\cos(\mu t),\dots,t ^{m_{j}-1}e^{\lambda t}\cos(\mu t)$<br>$e^{\lambda t}\sin(\mu t),te^{\lambda t}\sin(\mu t),\dots,t ^{m_{j}-1}e^{\lambda t}\sin(\mu t)$ |
### Method of undetermined coef $(\implies Y)$
Consider $\displaystyle L(y)=\sum_{k=0}^{n} a_{k}y^{(k)}=0$.
Characteristic equation: $\displaystyle\sum_{k=0}^{n}a_{k}r^{k}=0$, $m(r)\coloneqq$ multiplicity of $r$

| $g(t)$                                                                       | $Y(t)$                                                                           |
| :--------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| $P_{n}(t)$                                                                   | $t ^{m(0)}Q_{n}(t)$                                                              |
| $P_{n}(t)e^{\alpha t}$                                                       | $t ^{m(\alpha)}Q_{n}(t)e^{\alpha t}$                                             |
| $P_{n}(t)e^{\alpha t}\cos (\beta t)$<br>$P_{n}(t)e^{\alpha t}\sin (\beta t)$ | $t ^{m(\alpha+i\beta)}e^{\alpha t}(Q_{n}(t)\cos(\beta t)+R_{n}(t)\sin(\beta t))$ |

### Variation of parameters $(\implies Y)$
Consider $\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=g(t)$.
Let $y_{1},\dots,y_{n}$ form a fundamental set of solutions for $\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=0$.
==Solve==: Let $\displaystyle Y=\sum_{k=1}^{n}u_{k}y_{k}$, i.e. $\displaystyle Y(t)=\sum_{k=1}^{n}u_{k}(t)y_{k}(t)$.
$\displaystyle\implies\left\lbrace\begin{array}{l}u_{1}'y_{1}&+\cdots+&\mkern{-8pt}u_{n}'y_{n}&=0\\u_{1}'y_{1}'&+\cdots+&\mkern{-8pt}u_{n}'y_{n}'&=0\\\mkern{8pt}\vdots&\mkern{14pt}\vdots&\vdots&\ \vdots\\u_{1}'y_{1}^{(n-2)}\mkern{-10pt}&+\cdots+&\mkern{-8pt}u_{n}y_{n}^{(n-2)}\mkern{-8pt}&=0\\u_{1}'y_{1}^{(n-1)}\mkern{-10pt}&+\cdots+&\mkern{-8pt}u_{n}y_{n}^{(n-1)}\mkern{-8pt}&=g\end{array}\right.\implies \begin{bmatrix}y_{1}&y_{2}&\cdots&y_{n}\\y_{1}'&y_{2}'&\cdots&y_{n}'\\\vdots&\vdots&\ddots&\vdots\\y_{1}^{(n-2)}&y_{2}^{(n-2)}&\cdots&y_{n}^{(n-2)}\\y_{1}^{(n-1)}&y_{2}^{(n-1)}&\cdots&y_{n}^{(n-1)}\end{bmatrix}\begin{bmatrix}u_{1}'\\u_{2}'\\\vdots\\u_{n-1}'\\u_{n}'\end{bmatrix}=\begin{bmatrix}0\\0\\\vdots\\0\\g\end{bmatrix}$
Cramer's rule $\displaystyle \implies u_{k}'(t)=\frac{g(t)C_{m,n}(t)}{W(y_{1},\dots,y_{n})(t)}$, where $C_{m,n}=(-1)^{m+n}W(m|n)$ is the $(m,n)$-cofactor of $W(y_{1},\dots,y_{n})(t)$
