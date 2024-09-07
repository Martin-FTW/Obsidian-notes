# ODE techniques
General form: $F(x,y,y',\dots,y^{(n)})=0$
To solve: $y(x;c_{1},\dots,c_{n})$
## Any order
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
==Solve:== $\displaystyle y=\pm \sqrt[n-1]{ \frac{1}z }$ depending on odd/even.