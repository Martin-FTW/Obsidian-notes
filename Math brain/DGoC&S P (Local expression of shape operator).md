 Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition (Local expression of shape operator)
Let $S$ be an oriented surface with orientation $N$.
Let $p\in S$ and $\varphi:U\to S$ be a positively-oriented parametrization at $p$.
Then we have:
1. $[S_{p}]_{\beta}=\psi_{\beta}(\sff)(\psi_{\beta}(\fff))^{-1}=[A_{ij}][g_{ij}]^{-1}$
2. $\displaystyle K(p)=\det S_{p}=\frac{\det \psi_{\beta}(\sff)}{\det \psi_{\beta}(\fff)}=\frac{eg-f^{2}}{EG-F^{2}}$
3. $\displaystyle H(p)=\frac{1}{2}\tr S_{p}=\frac{k_{1}+k_{2}}{2}=\frac{1}{2}\frac{eG-2fF+gE}{EG-F^{2}}$
4. $\set{k_{1},k_{2}}= H\pm \sqrt{ H^{2}-K }$
#### Proof
Denote the standard basis $\beta=\set{\varphi_{u},\varphi_{v}}$ for $T_{p}S$.
Let $\alpha:(-\varepsilon,\varepsilon)\to U$ be a parametrized curve on $S$ with $\alpha(0)=p$.
Write $\alpha(t)=\varphi(u(t),v(t))$.
(Shorthands: $?'\to ?'(0),\varphi_{?}\to \varphi_{?}(p),N_{\_{}}\to N_{?}(p)\to(N\circ \varphi)_{?}(p)$)
1. $N=\dfrac{\varphi_{u}\times \varphi_{v}}{\norm{\varphi_{u}\times \varphi_{v}}}$ at $p$
2. $\alpha'=\varphi_{u}u'+\varphi_{v}v'$
3. $-dN_{p}(\alpha')=-(N\circ(u,v))'(0)=-N_{u}u'-N_{v}v'$
4. $\begin{cases}-N_{u}=a_{11}\varphi_{u}+a_{21}\varphi_{v}\\-N_{v}=a_{12}\varphi_{u}+a_{22}\varphi_{v}\end{cases}$, where $a_{ij}\in \mathbb{R}$ are given by $\beta$'s basis criterion for $-N_{u},-N_{v}\in T_{p}S$ at $p$
5. $-dN_{p}(\alpha')=(a_{11}u'+a_{12}v')\varphi_{u}+(a_{21}u'+a_{22}v')\varphi_{v}$ by 3 and 4
6.  $[S_{p}]_{\beta}\begin{bmatrix}u'\\v'\end{bmatrix}=[S_{p}(\alpha'))]_{\beta}=\begin{bmatrix}a_{11}&a_{12}\\a_{21}&a_{22}\end{bmatrix}\begin{bmatrix}u'\\v'\end{bmatrix}$
7. $[S_{p}]_{\beta}=[a_{ij}]$ by 6
8. $\sff_{p}(\alpha',\alpha')=\innerp{S(\alpha')}{\alpha'}{}=-\innerp{N_{u}u'+N_{v} v'}{\varphi_{u}u'+\varphi_{v}v'}{}=e(u')^{2}+2fu'v'+g(v')^{2}$
9. $\begin{cases}e=\innerp{-N_{u}}{\varphi_{u}}{}=a_{11}E+a_{21}F\\f=\innerp{-N_{u}}{\varphi_{v}}{}=a_{11}F+a_{21}G\\f=\innerp{-N_{v}}{\varphi_{u}}{}=a_{12}E+a_{22}F\\g=\innerp{-N_{v}}{\varphi_{v}}{}=a_{12}F+a_{22}G\end{cases}$ from 4
10. $\psi_{\beta}(\sff)=\begin{bmatrix}e&f\\f&g\end{bmatrix}=\begin{bmatrix}a_{11}&a_{12}\\a_{21}&a_{22}\end{bmatrix}\begin{bmatrix}E&F\\F&G\end{bmatrix}=[S_{p}]_{\beta}\psi_{\beta}(\fff)$
11. $[S_{p}]_{\beta}=\psi_{\beta}(\sff)(\psi_{\beta}(\fff))^{-1}=[A_{ij}][g_{ij}]^{-1}$ from 10
12. $\displaystyle K(p)=\det S_{p}=\frac{\det \psi_{\beta}(\sff)}{\det \psi_{\beta}(\fff)}=\frac{eg-f^{2}}{EG-F^{2}}$ from 11
13. $\displaystyle H(p)=\frac{1}{2}\tr S_{p}=\frac{k_{1}+k_{2}}{2}=\frac{1}{2}\frac{eG-2fF+gE}{EG-F^{2}}$, since $k_{1},k_{2}$ are eigenvalues of $S_{p}$, thus are solutions to $0=\det(S_{p}-tI_{T_{p}S})=\det \begin{bmatrix}a_{11}-t&a_{12}\\a_{21}&a_{22}-t\end{bmatrix}=t^{2}-(a_{11}+a_{22})t+\det S_{p}$
14. $k= H\pm \sqrt{ H^{2}-K }$ from $k^{2}-2Hk+K=\det(S_{p}-kI_{T_{p}S})=0$, where $k$ is an eigenvalue of $S_{p}$