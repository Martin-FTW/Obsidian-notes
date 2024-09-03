Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Theorem (Frenet equations)
Let $\alpha:I\to \mathbb{R}^{3}$ be a curve pbal.
Suppose $k(s)>0$ for all $s\in I$.
Then as functions of $s\in I$, we have $$\begin{bmatrix}T'\\N'\\B'\end{bmatrix}=\begin{bmatrix}
0 & k & 0 \\
-k & 0 & -\uptau \\
0 & \uptau & 0
\end{bmatrix}\begin{bmatrix}
T \\
N \\
B
\end{bmatrix}$$
That is:
- $T'(s)=k(s)N(s)$
- $N'(s)=-k(s)T(s)-\uptau(s)B(s)$
- $B'(s)=\uptau(s)N(s)$
### Modern notation
Let $\alpha:I\to \mathbb{R}^{3}$ be a curve pbal.
Suppose $k(s)>0$ for all $s\in I$.
Then as functions of $s\in I$, $\exists\uptau\in C^{\infty}(I)$ s.t. $$\begin{bmatrix}T'\\N'\\B'\end{bmatrix}=\begin{bmatrix}
0 & k & 0 \\
-k & 0 & \uptau \\
0 & -\uptau & 0
\end{bmatrix}\begin{bmatrix}
T \\
N \\
B
\end{bmatrix}$$
That is:
- $T'(s)=k(s)N(s)$
- $N'(s)=-k(s)T(s)+\uptau(s)B(s)$
- $B'(s)=-\uptau(s)N(s)$

We call $\uptau(s)$ the torsion of $\alpha$ at $s$.
#### Proof
Since $\set{T(s),N(s),B(s)}$ is a basis, $\exists! A\in \mathcal{M}_{3}(\mathbb{R})$ s.t. $\begin{bmatrix}T'&N'&B'\end{bmatrix}\transpose=A\begin{bmatrix}T&N&B\end{bmatrix}\transpose$ by [[LA T 2.6 (Unique basis map)]] 
Since $\set{T(s),N(s),B(s)}$ is an ONB $\forall s\in I$, we have
$$\begin{cases}
\innerp{T}{T}{}\equiv 1\\
\innerp{N}{N}{}\equiv 1\\
\innerp{B}{B}{}\equiv 1 
\end{cases}\implies\begin{cases}
\innerp{T'}{T}{}+\innerp{T}{T'}{}\equiv 0\\
\innerp{N'}{N}{}+\innerp{N}{N'}{}\equiv 0\\
\innerp{B'}{B}{}+\innerp{B}{B'}{}\equiv 0 
\end{cases}\implies\begin{cases}
\innerp{T'}{T}{}\equiv 0\\
\innerp{N'}{N}{}\equiv 0\\
\innerp{B'}{B}{}\equiv 0 
\end{cases}$$
Thus $A_{ii}=0$ for all $i\in\ii{1}{3}$ by [[LA T 6.5 (Orthonormal basis representation)]].
Now since $\alpha$ is pbal, we have $\displaystyle N= \frac{T'}{\norm{T}}=\frac{T'}{k}$.
Hence $T'=kN$, giving row $1$ of $A$.
Since $B=T\times N$, we have $B'=T'\times N+T\times N'=kN\times N+T\times N'=T\times N'\perp T$.
Hence $B'\times T\equiv 0$
Now $B'=\innerp{B'}{T}{}T+\innerp{B'}{N}{}N+\innerp{B'}{B}{}B=\uptau N$ by [[LA T 6.5 (Orthonormal basis representation)]].
Finally, $$\begin{cases}
\innerp{N}{T}{}\equiv 0 \\
\innerp{N}{B}{}\equiv 0
\end{cases}\implies \begin{cases}
\innerp{N'}{T}{}+\innerp{N}{T'}{}\equiv 0 \\
\innerp{N'}{B}{}+\innerp{N}{B'}{}\equiv 0
\end{cases}\implies \begin{cases}
\innerp{N'}{T}{}=-k \\
\innerp{N'}{B}{}=-\uptau
\end{cases}$$
Hence $N'=\innerp{N'}{T}{}T+\innerp{N'}{N}{}N+\innerp{N'}{B}{}B=-kT-\uptau B$ by [[LA T 6.5 (Orthonormal basis representation)]].
