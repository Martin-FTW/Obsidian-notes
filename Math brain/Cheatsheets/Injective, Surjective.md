# Injective, Surjective
Let $X,Y$ be sets and $f:X\to Y$ be a function.
Then the each column consists of equivalent statements:

|                                                                            $f$ is injective                                                                            |                                                                                     $f$ is surjective                                                                                      |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                       $\forall A\subseteq X:f^{-1}(f(A))\subseteq A$ <br> $\forall A\subseteq X:f^{-1}(f(A))= A$                                       |                                                 $\forall B\subseteq Y:f(f^{-1}(B))\supseteq B$ <br> $\forall B\subseteq Y:f(f^{-1}(B))= B$                                                 |
|                                                        $\forall A\subseteq X:\exists B\subseteq Y:A=f^{-1}(B)$                                                         |                                                                     $\forall B\subseteq Y:\exists A\subseteq X:B=f(A)$                                                                     |
| $\forall A_{1},A_{2}\subseteq X:f(A_{1})\subseteq f(A_{2})\implies A_{1}\subseteq A_{2}$ <br> $\forall A_{1},A_{2}\subseteq X:f(A_{1})= f(A_{2})\implies A_{1}= A_{2}$ | $\forall B_{1},B_{2}\subseteq Y:f^{-1}(B_{1})\subseteq f^{-1}(B_{2})\implies B_{1}\subseteq B_{2}$ <br> $\forall B_{1},B_{2}\subseteq Y:f^{-1}(B_{1})= f^{-1}(B_{2})\implies B_{1}= B_{2}$ |
|       $\forall A_{\alpha}\subseteq X:f(\cap A_{\alpha})\supseteq \cap f(A_{\alpha})$ <br> $\forall A_{\alpha}\subseteq X:f(\cap A_{\alpha})=\cap f(A_{\alpha})$        |                                                                                                                                                                                            |
|                                                                                                                                                                        |                                                              $\forall A\subseteq X:f(X\setminus A)\supseteq Y\setminus f(A)$                                                               |
|                                                     $\exists g\in X^{Y}:g\circ f=\id_{X}$ <br> left-inverse exists                                                     |                                                     $\exists g\in X^{Y}:f\circ g=\id_{Y}$ <br> right-inverse exists (Requires choice)                                                      |
|              $\forall Z:\forall g_{1},g_{2}\in X^{Z}:f\circ g_{1}=f\circ g_{2}\implies g_{1}=g_{2}$ <br> left-cancellative: a $\mathsf{Set}$-monomorphism              |                        $\forall Z:\forall g_{1},g_{2}\in Y^{Z}:g_{1}\circ f=g_{2}\circ f\implies g_{1}=g_{2}$ <br> right-cancellative: a $\mathsf{Set}$-epimorphism                        |