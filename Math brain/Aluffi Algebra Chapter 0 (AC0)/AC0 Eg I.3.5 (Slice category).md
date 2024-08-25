Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Example I.3.5 (Slice category)
Let $\mathsf{C}$ be a category and $A\in \obj(\mathsf{C})$.
Define $\mathsf{C}_{A}$ by
- $\obj(\mathsf{C}_{A})=\set{(f,Z)\given Z\in \obj \mathsf{C},f\in\hom(Z,A)}$, i.e. every object is a top-down arrow from an object $Z$ of $\mathsf{C}$ to $A$ 
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAC0QBfU9TXfIRRkAjFVqMWbAILdxMKAHN4RUADMAThAC2SMiBwQkI6vWatEINXK5A
\begin{tikzcd}
Z \arrow[d, "f"] \\
A \end{tikzcd}
\end{document}
```
- $\forall$ objects $(f_{1},Z_{1}),(f_{2},Z_{2})$, $\hom_{\mathsf{C}_{A}}((f_{1},Z_{1}),(f_{2},Z_{2}))=\set{\sigma\in \hom_{\mathsf{C}}(Z_{1},Z_{2})\given f_{1}=f_{2}\sigma}$, i.e. the set of all morphisms $\sigma$ that makes the following diagram commute: 
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAC0B9ARhAF9S6TLnyEU3Utyq1GLNgEF+gkBmx4CRAEzlp9Zq0QdOm-tJhQA5vCKgAZgCcIAWyRkQOCEgkz9bWzyU7RxdEbXdPRG89OUN-EwEg51dqDyQw6IMQAB0s7AsnOlM+IA
\begin{tikzcd}
Z_1 \arrow[rd, "f_1"] \arrow[rr, "\sigma"] & & Z_2 \arrow[ld, "f_2"] \\ & A & \end{tikzcd}
\end{document}
```
#### Proof
Identity: $\forall$ object $f:Z\to A$, $1_{f}\coloneqq1_{Z}$ is the identity.
Composition: $\forall$ morphism $\sigma:f_{1}\to f_{2},\tau: f_{2}\to f_{3}$, $\tau \sigma$ defined by the composition in $\mathsf{C}$ will make $f_{1}=f_{3}\tau \sigma$:
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAC0B9ARhAF9S6TLnyEU3clVqMWbLgCZ+gkBmx4CReZOr1mrRB04BmJULWiiE7lN2yDAQX5SYUAObwioAGYAnCAFskMhAcCCQjHRl9EC8eUxi-QMQJELDECOk9NljFAW9EpC1U8Misg1iTPISAoOpQpBTbaIAdZuxXfzp43xrkurSiprZWnDomboLEYPrEIoAjGDAocOChgxGx1vbOpz4gA
\begin{tikzcd}
Z_1 \arrow[rd, "f_1"] \arrow[r, "\sigma"] \arrow[rr, "\tau\sigma", bend left] & Z_2 \arrow[d, "f_2"] \arrow[r, "\tau"] & Z_3 \arrow[ld, "f_3"] \\ & A & \end{tikzcd}
\end{document}
```
