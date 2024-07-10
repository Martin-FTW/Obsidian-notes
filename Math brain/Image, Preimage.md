# Image, Preimage
Let $X,Y$ be sets and $f:X\to Y$ be a function
## Multiple subsets
Let $A_{\alpha}\subseteq X,B_{\alpha}\subseteq Y$ for all $\alpha\in \mathcal{A}$. Then:

|                                                        $f$                                                         |                              $f^{-1}$                               |
| :----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------: |
|                             $A_{1}\subseteq A_{2}\implies f(A_{1})\subseteq f(A_{2})$                              | $A_{1}\subseteq A_{2}\implies f^{-1}(A_{1})\subseteq f^{-1}(A_{2})$ |
|                                      $f(\cup A_{\alpha})=\cup f(A_{\alpha})$                                       |          $f^{-1}(\cup A_{\alpha})=\cup f^{-1}(A_{\alpha})$          |
|        $f(\cap A_{\alpha})\subseteq \cap f(A_{\alpha})$<br>"$=$" if $f\vert_{\cup A_{\alpha}}$ is injective        |         $f^{-1}(\cap A_{\alpha})= \cap f^{-1}(A_{\alpha})$          |
| $f(A_{1}\setminus A_{2})\supseteq f(A_{1})\setminus f(A_{2})$<br> "$=$" if $f\vert_{A_{1}\cup A_{2}}$ is injective |        $f(A_{1}\setminus A_{2})=f(A_{1})\setminus f(A_{2})$         |

## Single subset
Let $A\subseteq X,B\subseteq Y$. Then:

| $f$ | $f^{-1}$ |
|:---:|:---:|
| $f(f^{-1}(B))\subseteq B$ <br> "$=$" if $B\subseteq f(X)$ | $f^{-1}(f(A))\supseteq A$ <br> "$=$" if $f\vert_{A}$ is injective |
| $f(f^{-1}(f(A)))=A$ | $f^{-1}(f(f^{-1}(B)))=B$ |
| $f(A\cup f^{-1}(B))\subseteq f(A)\cup B$ | $f^{-1}(f(A)\cup B)\supseteq A\cup f^{-1}(B)$ |
| $f(A\cap f^{-1}(B))= f(A)\cup B$ | $f^{-1}(f(A)\cap B)\supseteq A\cup f^{-1}(B)$ |
| $f(A)\cap B=f\vert^B(A)$ | $f^{-1}(B)\cap A=f\vert_{A}^{-1}(B)$ |

