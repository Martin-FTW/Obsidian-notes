Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Covectors, differential forms)
Recall a $k$-tensor is a $k$-linear function $f:V^{k}\to \mathbb{R}$.
It is alternating if $\forall \sigma\in S_{k}:\sigma f=(\sgn \sigma)f$ i.e. $f(v_{\sigma(1)},\dots,v_{\sigma(k)})=(\sgn \sigma)f(v_{1},\dots,v_{k})$
We call alternating $k$-tensors on $V$ a *$k$-covector* on $V$.
The set of all $k$-covectors is denoted $A_{k}(V)$, or $\bigwedge^{k}(V\dual)$ by the exterior algebra construction.
The vector space $A_{k}(T_{p}M)$ is denoted by $\bigwedge^{k}(T_{p}^*M)$.
A function $\omega$ mapping $p\in M$ to a $k$-covector $\omega_{p}\in \bigwedge^{k}(T_{p}^*M)$ is called a *differential $k$-form on $M$*.
A *top form* is a $k$-form where $k=\dim M$.

Similar to [[AItM Ep (Induced linear map on vector fields by 1-form)]], we have the induced $k$-linear map for vector fields $X_{1},\dots,X_{k}$ where $\omega(X_{1},\dots,X_{k})$ is defined by $(\omega(X_{1},\dots,X_{k}))(p)=\omega_{p}((X_{1})_{p},\dots,(X_{k})_{p})$.