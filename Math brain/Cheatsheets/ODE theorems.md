# ODE theorems
General form: $F(x,y,y',\dots,y^{(n)})=0$
To solve: $y(x;c_{1},\dots,c_{n})$
Wronskian: for $y=(y_{1},\dots,y_{n})\in(C(I))^{n}:$$W(y_{1},\dots,y_{n})(t)=\begin{vmatrix}y(t)\\y'(t)\\\vdots\\y^{(n-1)}(t)\end{vmatrix}=\begin{vmatrix}y_{1}(t)&y_{2}(t)&\cdots&y_{n}(t)\\y_{1}'(t)&y_{2}'(t)&\cdots&y_{n}'(t)\\\vdots&\vdots&\ddots&\vdots\\y_{1}^{(n-1)}(t)&y_{2}^{(n-1)}(t)&\cdots&y_{n}^{(n-1)}(t)\end{vmatrix}$
## Any order
## First order $n=1$
### Linear $y'+p(x)y=q(x)\iff F(x,y,y')=Ly+q(x)$
Let $I=\opop{a}{b},t_{0}\in I$ and $p,q\in C(I),y_{0}\in \mathbb{R}$
Then $\begin{cases}y'+p(t)y=q(t)\\y(t_{0})=y_{0}\end{cases}$ has unique solution on $I$.
### Picard-Lindelof $y'=f(t,y)$ Lipschitz
Let $\Omega=\clcl{a}{b}\times \clcl{c}{d},(t_{0},y_{0})\in \interior\Omega$, $f:\Omega \to \mathbb{R},y_{0}\in \mathbb{R}$.
Suppose $\forall (t,y)\in \Omega:f(\cdot,y)$ is continuous and $f(t,\cdot)$ is Lipschitz.
Then $\exists h>0:\begin{cases}y'=f(t,y)\\y(t_{0})=y_{0}\end{cases}$ has unique solution on $\clcl{t_{0}-h}{t_{0}+h}$
#### Picard iteration
$\displaystyle y_{k+1}(t)=y_{0}+\int_{t_{0}}^{t}f(s,y_{k}(s))\d s$
### Cauchy-Peano $y'=f(t,y)$ continuous
Let $\Omega=\opop{a}{b}\times \opop{c}{d},(t_{0},y_{0})\in \Omega$, $f\in C(\Omega),y_{0}\in \mathbb{R}$
Then $\exists h>0:\begin{cases}y'=f(t,y)\\y(t_{0})=y_{0}\end{cases}$ has a solution on $\opop{t_{0}-h}{t_{0}+h}$
### Extension of local solution
Let $\Omega \subseteq \mathbb{R}^{2}$ open, $(t_{0},y_{0})\in \Omega$, $f\in C(\Omega),y_{0}\in \mathbb{R}$, $K\subseteq \mathbb{R}$ compact.
Suppose $y:K\to \mathbb{R}$ is a solution to $\begin{cases}y'=f(t,y)\\y(t_{0})=y_{0}\end{cases}$.
Then $\exists U\supseteq K$ s.t. $\tilde{y}:U\to \mathbb{R}$ is an extension of $y$ and $U$ touches $\partial \Omega$
## Second order $n=2$
### Existence and uniqueness
Let $I=\opop{a}{b}\subseteq \mathbb{R},t_{0}\in I$ and $p,q,g\in C(I),y_{0},y_{0}'\in \mathbb{R}$.
Then $\begin{cases}y''+p(t)y'+q(t)y=g(t)\\y(t_{0})=y_{0},y'(t_{0})=y_{0}'\end{cases}$ has unique solution in $I$.
### Wronskian and linear independence
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $f,g\in C(I)$
Then $[\exists t_{0}\in I:W(f,g)(t_{0})\neq 0]\implies f,g$ are linearly independent
Converse holds if $f,g$ solves $y''+py'+qy=0$, where $p,q\in C(I)$
### Abel's theorem
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $p,q\in C(I)$.
Suppose $y_{1},y_{2}:I\to \mathbb{R}$ solves $y''+py'+qy=0$.
Then $\exists C\in \mathbb{R}:W(y_{1},y_{2})=Ce^{-\int p}$ on $I$, i.e. $\forall t\in I:W(y_{1},y_{2})(t)=Ce^{-\int p(t)\d t}$
### Characterization of fundamental set
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $p,q\in C(I)$.
Let $y_{1},y_{2}:I\to \mathbb{R}$ solve $L(y)=y''+p(t)y'+q(t)y=0$.
Then TFAE:
1. $\exists t_{0}\in I:W(y_{1},y_{2})(t_{0})\neq 0$
2. $\forall t\in I:W(y_{1},y_{2})(t)\neq 0$
3. $y_{1},y_{2}$ are $\mathbb{R}$-linearly independent as functions on $I$
4. $y_{1},y_{2}$ form a fundamental set of solutions to $L(y)=0$
5. $y_{1},y_{2}$ form a basis for $\ker L$
6. $\forall t_{0}\in I:$ the map $T_{t_{0}}:\ker L\to \mathbb{R}^{2},T_{t_{0}}(y)=(y(t_{0}),y'(t_{0}))$ is a linear isomorphism
### Structure of solutions
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $p,q,g \in C(I)$.
Let $y_{1},y_{2},Y:I\to \mathbb{R}$ solve $y''+p(t)y'+q(t)y=g(t)$.
Suppose $y_{1},y_{2}$ form a fundamental set of solutions of $y''+p(t)y'+q(t)y=0$ while $Y$ is any particular solution.
Then $Y+\span \set{y_{1},y_{2}}$ is the solution set.
i.e. $\forall$ solution $y:I\to \mathbb{R}$, $\exists! c_{1},c_{2}\in \mathbb{R}:y(t)=c_{1}y_{1}(t)+c_{2}y_{2}(t)+Y(t)$.
## Higher order $n$
### Existence and uniqueness
Let $I=\opop{a}{b}\subseteq \mathbb{R},t_{0}\in I$ and $p_{0},\dots,p_{n-1},g\in C(I),y_{0},\dots,y_{0}^{(n-1)}\in \mathbb{R}$.
Then $\begin{cases}\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=g(t)\\y^{(k)}(t_{0})=y_{0}^{(k)}\end{cases}$ has unique solution in $I$.
### Wronskian and linear independence
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $y=(y_{1},\dots,y_{n})\in (C^{n}(I))^{n}$
Then $[\exists t_{0}\in I:W(y)(t_{0})\neq 0]\implies [y_{1},\dots,y_{n}$ are linearly independent$]$
Converse holds if $y_{1},\dots,y_{n}$ solves $\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=0$, where $p_{0},\dots,p_{n-1}\in C(I)$
### Abel's theorem
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $p_{0},\dots,p_{n-1}\in C(I)$.
Suppose $y_{1},\dots,y_{n}:I\to \mathbb{R}$ solves $\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=0$.
Then $\exists C\in \mathbb{R}:W(y_{1},\dots,y_{n})=Ce^{-\int p_{n-1}}$ on $I$, i.e. $\forall t\in I:W(y_{1},\dots,y_{n})(t)=Ce^{-\int p_{n-1}(t)\d t}$
### Characterization of fundamental set
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $p_{0},\dots,p_{n-1}\in C(I)$.
Let $y_{1},\dots,y_{n}:I\to \mathbb{R}$ solve $L(y)=\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=0$.
Then TFAE:
1. $\exists t_{0}\in I:W(y_{1},\dots,y_{n})(t_{0})\neq 0$
2. $\forall t\in I:W(y_{1},\dots,y_{n})(t)\neq 0$
3. $y_{1},\dots,y_{n}$ are $\mathbb{R}$-linearly independent as functions on $I$
4. $y_{1},\dots,y_{n}$ form a fundamental set of solutions to $L(y)=0$
5. $y_{1},\dots,y_{n}$ form a basis for $\ker L$
6. $\forall t_{0}\in I:$ the map $T_{t_{0}}:\ker L\to \mathbb{R}^{n},T_{t_{0}}(y)=(y(t_{0}),y'(t_{0}),\dots,y^{(n-1)}(t_{0}))$ is a linear isomorphism
### Structure of solutions
Let $I=\opop{a}{b}\subseteq \mathbb{R}$ and $p_{0},\dots,p_{n-1},g \in C(I)$.
Let $y_{1},\dots,y_{n},Y:I\to \mathbb{R}$ solve $\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=g(t)$.
Suppose $y_{1},\dots,y_{n}$ form a fundamental set of solutions of $\displaystyle  y^{(n)}+\sum_{k=0}^{n-1} p_{k}(t)y^{(k)}=0$ while $Y$ is any particular solution.
Then $Y+\span \set{y_{1},\dots,y_{n}}$ is the solution set.
i.e. $\forall$ solution $y:I\to \mathbb{R}$, $\displaystyle \exists! c_{1},\dots,c_{n}\in \mathbb{R}:y(t)=Y(t)+\sum_{k=1}^{n}c_{k}y_{k}(t)$.