Book: [[Munkres Topology (MT)]]
# Corollary 22.3 (Topological First Isomorphism theorem)
Let $g:X\to Z$ be a surjective continuous map.
Let $X^{*}=\set{g^{-1}(\set{z})\given z\in Z}$ be a partition of $X$.
Let $g$ induce the quotient topology on $X$.
Then $\exists!$ bijective continuous $f:X^{*}\to Z$ s.t. $g=f\circ p$.
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAA0QBfU9TXfIRRkAjFVqMWbdgD0AVN14gM2PASIjSY6vWatEIAFrdxMKAHN4RUADMAThAC2SMiBwQkmkAzoAjGAwACvxqQiB2WOYAFjggOpL6IAA6SWhYirYOzohe7kgATPF6bCkwAB5YcDhwAIQABDZx3n4BwaqCbBHRsTyZTi7UeYiFEsUGKTYQdowMdeZNUTB0UGw4AO4Qi8sIvSD2-TmDHsNFUuNJ2M5cFFxAA
\begin{tikzcd}
X \arrow[d, "\pi"'] \arrow[rd, "\forall g", two heads] & \\
X^* \arrow[r, "\exists! f"'] \arrow[r, "\sim"] & Z
\end{tikzcd}
\end{document}
```
In this case, we have
- $f$ is a homeomorphism iff $g$ is a quotient map
- If $Z$ is Hausdorff then $X^{*}$ is Hausdorff