# C1 implies differentiable
Let $f:\mathbb{R}^{n}\to \mathbb{R}$ and $a\in \mathbb{R}^{n}$
Suppose $f$ is $C^{1}$.
Then $f$ is differentiable.
#### Proof
Let $\varepsilon>0$.
$\forall i\in\ii{1}{n}$, since $\displaystyle \frac{ \partial f}{ \partial x^{i} }$ is continuous at $a$, we have $\displaystyle \exists \delta_{i}>0:\forall t\in B(\delta_{i},a):\abs*{\frac{ \partial f}{ \partial x^{i} }(t)-\frac{ \partial f}{ \partial x^{a)} }}<\frac{\varepsilon}{n}\quad (*)$
Take $\delta =\min \set{\delta_{i}}_{i=1}^{n}$. Let $x=(x^{1},\dots,x^{n})\in B(\delta,a)$.
Let $\displaystyle u_{j}=\sum_{k=1}^{j}a^{k}e_{k}+\sum_{k=j+1}^{n}x^{k}e_{k}=(a^{1},\dots,a^{j},x^{j+1},\dots,x^{n})$. Then $u_{0}=x,u_{n}=a$.
By MVT, $\exists \xi^{1}\in \opop{a^{1}}{x^{1}}\cup \opop{x^{1}}{a^{1}}$ s.t. $\displaystyle f(u_{0})-f(u_{1})=\frac{ \partial f}{ \partial x^{1} }(b_{1})(x^{1}-a^{1})$, where $\displaystyle b_{1}=\xi^{1}e_{1}+\sum_{k=2}^{n}x^{k}e_{k}=(\xi^{1},x^{2},\dots,x^{n})$.
Inductively for all $i\in\ii{2}{n}$, $\exists \xi^{i}\in \opop{a^{i}}{x^{i}}\cup \opop{x^{i}}{a^{i}}$ s.t. $\displaystyle f(u_{i-1})-f(u_{i})=\frac{ \partial f}{ \partial x^{i} }(b_{i})(x^{i}-a^{i})$, where $\displaystyle b_{i}=\sum_{k=1}^{i}\xi^{k}e_{k}+\sum_{k=i+1}^{n}x^{k}e_{k}=(\xi_{1},\dots,\xi^{i},x^{i+1},\dots,x^{n})$.
Note that for all $i\in\ii{1}{n}$: $$\begin{align}\displaystyle \norm{b_{i}-a}&=\norm*{\sum_{k=1}^{i}(\xi^{k}-a^{k})e_{k}+\sum_{k=i+1}^{n}(x^{k}-a^{k})e_{k}}\\&=\sqrt{ \sum_{k=1}^{i}(\xi^{k}-a^{k})^{2}+\sum_{k=i+1}^{n}(x^{k}-a^{k})^{2} }\\&\leq \sqrt{ \sum_{k=1}^{n}(x^{k}-a^{k})^{2} }\\&=\norm{x-a}\\&<\delta\\&\leq \delta_{i}\end{align}$$
Hence $\displaystyle\abs*{\frac{ \partial f}{ \partial x^{i} }(b_{i})-\frac{ \partial f}{ \partial x^{i} }(a)}< \frac{\varepsilon}{n}$ by $(*)$.
Now $$\begin{align}
\abs*{\frac{\displaystyle f(x)-f(a)-\sum _{i=1}^{n}\frac{ \partial f}{ \partial x^{i} }(a)(x^{i}-a^{i})}{\norm{x-a}}}
&= \frac{\abs*{\displaystyle f(u_{0})-f(u_{n})-\sum _{i=1}^{n}\frac{ \partial f}{ \partial x^{i} }(a)(x^{i}-a^{i})}}{\norm{x-a}} \\
&= \frac{\abs*{\displaystyle \sum _{i=1}^{n} \left( \frac{ \partial f}{ \partial x^{i} }(b_{i})-\frac{ \partial f}{ \partial x^{i} }(a) \right)(x^{i}-a^{i})}}{\norm{x-a}} \\
&\leq \sum_{i=1}^{n}\abs*{\left( \frac{ \partial f}{ \partial x^{i} }(b_{i})-\frac{ \partial f}{ \partial x^{i} }(a) \right)}\cdot \frac{\abs{x^{i}-a^{i}}}{\norm{x-a}} \\
&<n\cdot \frac{\varepsilon}{n}\cdot1 \\
&=\varepsilon
\end{align} $$