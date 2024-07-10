# Implicit function theorem
Let $\Omega$ be an open set in $\mathbb{R}^{n+m}$ and $a\in \mathbb{R}^{n},b,c\in \mathbb{R}^{m}$ s.t. $a\concat b\in \Omega$
Let $r\in \mathbb{Z}_{>0}\cup \set{\infty,\omega}$
Let $F:\Omega\to\mathbb{R}^m$ be $C^r$ with $F(a\concat b)=c$
Denote $x=(x_1,\cdots,x_n),y=(y_1,\cdots,y_m)$ and similarly for $a,b,c$, and $$F(x\concat y)=
\begin{bmatrix}
F_1(x_1,\cdots,x_n,y_1,\cdots,y_n)\\
\vdots\\
F_m(x_1,\cdots,x_n,y_1,\cdots,y_n)
\end{bmatrix}$$
Note that $$JF=\begin{bmatrix}\begin{array}{ccc|ccc}
\frac{\partial F_1}{\partial x_1} &\cdots & \frac{\partial F_1}{\partial x_n} & \frac{\partial F_1}{\partial y_1} &\cdots & \frac{\partial F_1}{\partial y_m} \\
\vdots & \ddots & \vdots & \vdots & \ddots & \vdots\\
\frac{\partial F_m}{\partial x_1} & \cdots & \frac{\partial F_m}{\partial x_n} & \frac{\partial F_1}{\partial y_1} &\cdots & \frac{\partial F_1}{\partial y_m} 
\end{array}\end{bmatrix}=\bigg[\left[\frac{\partial F_i}{\partial x_k}\right]_{m\times n}\bigg|\left[\frac{\partial F_i}{\partial y_j}\right]_{m\times m}\bigg]$$
Suppose the following equivalent statements hold:
- $\displaystyle \left[\left.\frac{\partial F_i}{\partial y_j}\right|_{a\concat b}\right]_{m\times m}$ is invertible/nonsingular
- $\det\displaystyle \left[\left.\frac{\partial F_i}{\partial y_j}\right|_{a\concat b}\right]_{m\times m}\neq 0$

Then the followinmg equivalent statements hold: 
- $y$ is a local $C^{r}$ function of $x$ at $a$ which returns $b$.
- $\exists$ nbhd $U\subseteq\mathbb{R}^n$ of $a$, $V\subseteq\mathbb{R}^m$ of $b$ s.t. $\exists!\varphi:U\to V:$
	1. $\varphi$ is $C^r$
	2. $\varphi(a)=b$
	3. $F(x\concat\varphi(x))=c$ for any $x\in U$
	4. For any $x\in U$, $$\left[\frac{\partial \varphi_j}{\partial x_k}(x)\right]_{m\times n}=-\left[\frac{\partial F_i}{\partial y_j}(x\concat\varphi(x))\right]_{m\times m}^{-1}\left[\frac{\partial F_i}{\partial x_k}(x\concat\varphi(x))\right]_{m\times n}$$

## m=1
Let $\Omega\in \mathbb{R}^{n+1}$ be open and $c\in \mathbb{R}$.
Let $r\in \mathbb{Z}_{>0}\cup \set{\infty,\omega}$
Let $F:\Omega\to \mathbb{R}$ be $C^{r}$ denoted $F=F(x_{1},\dots,x_{n},y)$
Let $p=(a_{1},\dots,a_{n},b)\in F^{-1}(\set{c})$ with $\left.\dfrac{ \partial F }{ \partial y }\right|_{p}\neq 0$.
Then $\exists$ open $U\subseteq \mathbb{R}^{n}$ and nbhd $V$ of $p$ s.t. $\exists!\varphi:U\to \mathbb{R}:$
1. $\varphi$ is $C^{r}$
2. $\varphi(a_{1},\dots,a_{n})=b$
3. $F^{-1}(\set{c})\cap V=\graph(\varphi)$