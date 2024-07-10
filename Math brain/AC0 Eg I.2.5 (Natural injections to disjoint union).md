Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Example I.2.5 (Natural injections to disjoint union)
Let $A,B$ be sets.
Then there are natural injections
```tikz
\usepackage{tikz-cd}\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAEEQBfU9TXfIRQAmclVqMWbAELdeIDNjwEiARlKrx9Zq0QcAOvoDGENACdoAAlldxMKAHN4RUADMLAWyRkQOCElFfOiwGNgALCAgAazk3TyR1X39EQIAjGDAob2o4MKxXHGyQMJg6LMQwJgYGahxg0L0I6MZC2y4gA
\begin{tikzcd}
A \arrow[rd, hook] & & B \arrow[ld, hook'] \\ & A\coprod B & \end{tikzcd}
\end{document}
```
from $A,B$ to their disjoint union by sending each element to their corresponding element in the isomorphic copy of $A,B$ in $A\coprod B$.