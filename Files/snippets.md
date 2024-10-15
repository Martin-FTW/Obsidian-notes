/*
```js
*/
[    
    // Math mode
    {trigger: "mk", replacement: "$$0$", options: "tA"},
    {trigger: "dm", replacement: "$$$0$$", options: "tAw"},
    {trigger: "beg", replacement: "\\begin{$0}\n$1\n\\end{$0}", options: "mA"},
    {trigger: "\\\$((?:(?!\\\$).)*?)disp", replacement: "\$\\displaystyle [[0]]", options: "rmA"},

	// Links

	// Note templates
	{trigger: "vecf", replacement: "Let $F$ be a field and $V$ be a vector space over $F$.\n", options: "tA"},
	{trigger: "vecK", replacement: "Let $K$ be a field and $V$ be a vector space over $K$.\n", options: "tA"},
	{trigger: "vecr", replacement: "Let $V$ be a vector space over $\\mathbb{R}$.\n", options: "tA"},
	{trigger: "topsp", replacement: "Let $(X,\\mathscr\{T\})$ be a topological space.\n", options: "tA"},
	{trigger: "\\(([UV]),\\\\p([sh])i", replacement: "([[0]],\\p[[1]]i)=([[0]],${0:x}^{1},\\dots,${0:x}^{${1:n}}$2", options: "rm", priority: 10},
	{trigger: "fo_{r}ier", replacement: "a_{0}+\\sum_{n=1}^{\\infty} (a_{n}\\cos(nx)+b_{n}\\sin(nx))", options: "m", priority: 10},
	{trigger: "a_{0}+\\sum_{n=1}^{\\infty} (a_{n}\\cos(nx)+b_{n}\\sin(nx))", replacement: "\\sum_{n=0}^{\\infty}(\\cos(nx)+b_{n}\\sin(nx))", options: "m", priority: 10},
	{trigger: "\\sum_{n=0}^{\\infty}(\\cos(nx)+b_{n}\\sin(nx))", replacement: "\\sum(\\cos(nx)+b_{n}\\sin(nx))", options: "m", priority: 10},
	{trigger: "\\sum(\\cos(nx)+b_{n}\\sin(nx))", replacement: "a_{0}+\\sum_{n=1}^{\\infty} (a_{n}\\cos(nx)+b_{n}\\sin(nx))", options: "m", priority: 10},
    {trigger: "ext", replacement: "\\bigwedge^{${1:k}}($2)", options: "mA"},

    // Dashes
    // {trigger: "--", replacement: "–", options: "tA"},
    // {trigger: "–-", replacement: "—", options: "tA"},
    // {trigger: "—-", replacement: "---", options: "tA"},
    //Symbols
    {trigger: "++", replacement: "\\concat", options: "mA"},
    {trigger: "lr", replacement: "\\leftrightarrow", options: "m"},
    {trigger: "cdot", replacement: "\\cdot", options: "mA", priority: 2},
    {trigger: ":=", replacement: "\\coloneqq", options: "mA", priority: 2},
    {trigger: "div", replacement: "\\divides", options: "mA", priority: 2},
    {trigger: "\\s+ast", replacement: "^*", options: "rmA"},
    {trigger: "(\\\\frac(?!.*\\\\frac)\\{.*?\\}\\{.*?\\})at", replacement: "\\left.[[0]]\\right\\vert_{$1}$2", options: "rmA", priority: 2},
    {trigger: "at(.)", replacement: "\\vert_{[[0]]}$1", options: "rm", priority: 1},

    // Integer intervals
    {trigger: "]]", replacement: "\\ii{$0}{$1}$2", options: "mA"},

    // Sets
    {trigger: "pos", replacement: "\\mathbb\{Z\}_\{>0\}", options: "mA"},
    {trigger: "mat", replacement: "\\mathcal\{M\}_\{$0,$1\}($2)", options: "mA"},
    {trigger: "empty", replacement: "\\emptyset", options: "mA"},

    // Override
    {trigger: "\\nu llity", replacement: "\\nullity", options: "mA"},
    {trigger: "lim", replacement: "\\lim", options: "mA", priority: 1},
    {trigger: "\\supp", replacement: "\\supp", options: "mA", priority: 10},
    {trigger: "\\dot\{v\}s", replacement: "\\vdots", options: "mA"},
    {trigger: "\\cdots", replacement: "\\cdots", options: "mA", priority: 10},
    {trigger: "ddots", replacement: "\\ddots", options: "mA"},
    {trigger: "t\\imes", replacement: "\\times", options: "mA", priority: 1},
    {trigger: "ot\\imes", replacement: "\\otimes", options: "mA", priority: 2},
    {trigger: "bigcup", replacement: "\\bigcup", options: "mA", priority: 2},
    {trigger: "bigcap", replacement: "\\bigcap", options: "mA", priority: 2},
    {trigger: "gg", replacement: "gg", options: "mA", priority: 2},
    {trigger: "ll", replacement: "ll", options: "mA", priority: 2},
    {trigger: "bigsqcup", replacement: "\\bigsqcup", options: "mA", priority: 2},
    {trigger: "bigsqcap", replacement: "\\bigsqcap", options: "mA", priority: 2},
    {trigger: "\\xi nn", replacement: "x\\in", options: "mA", priority: 2},
    {trigger: "\\inf ty", replacement: "\\infty", options: "mA", priority: 2},
    {trigger: "d_\{a\}l", replacement: "\\dual", options: "mA", priority: 2},
    {trigger: "ot\\im es", replacement: "\\otimes", options: "mA", priority: 2},
    {trigger: "\\cotp", replacement: "T_{${0:p}}^*${1:M}$2", options: "mA", priority: 2},
    {trigger: "_{p}tau", replacement: "\\uptau", options: "mA", priority: 2},
    {trigger: "\\dome", replacement: "d\\omega", options: "mA", priority: 10},
    {trigger: "_{p}tau", replacement: "\\uptau", options: "mA", priority: 10},
    {trigger: "eq_{i}v", replacement: "\\equiv", options: "mA", priority: 10},

	//brackets
	
    {trigger: "\\cl cl", replacement: "\\clcl{$0}{$1}", options: "mA", priority: 10},
    {trigger: "opcl", replacement: "\\opcl{$0}{$1}", options: "mA", priority: 10},
    {trigger: "\\cl op", replacement: "\\clop{$0}{$1}", options: "mA", priority: 10},
    {trigger: "lie", replacement: "\\lie{$0}{$1}", options: "mA", priority: 10},
    //macros
    {trigger: "\\in er", replacement: "\\innerp\{$0\}\{$1\}\{\}$2", options: "mA"},
    {trigger: "ind", replacement: "\\ind\{$0\}$1", options: "mA"},
    {trigger: "wed", replacement: "\\wedge", options: "mA"},
    {trigger: "pb", replacement: "\\pullback", options: "mA"},
    {trigger: "pf", replacement: "\\pushforward", options: "mA"},
    {trigger: "\\\\pushforward(,.)", replacement: "\\pushforward\[[[0]]\]", options: "mAr"},
    
    
    // Greek letters
    {trigger: "@a", replacement: "\\alpha", options: "mA"},
    {trigger: "@A", replacement: "\\alpha", options: "mA"},
    {trigger: "@b", replacement: "\\beta", options: "mA"},
    {trigger: "@B", replacement: "\\beta", options: "mA"},
    {trigger: "@c", replacement: "\\chi", options: "mA"},
    {trigger: "@C", replacement: "\\chi", options: "mA"},
    {trigger: "@g", replacement: "\\gamma", options: "mA"},
    {trigger: "@G", replacement: "\\Gamma", options: "mA"},
    {trigger: "@d", replacement: "\\delta", options: "mA"},
    {trigger: "@D", replacement: "\\Delta", options: "mA"},
    {trigger: "@e", replacement: "\\epsilon", options: "mA"},
    {trigger: "@E", replacement: "\\epsilon", options: "mA"},
    {trigger: "vare", replacement: "\\varepsilon", options: "mA"},
    {trigger: "@z", replacement: "\\zeta", options: "mA"},
    {trigger: "@Z", replacement: "\\zeta", options: "mA"},
    {trigger: "@t", replacement: "\\theta", options: "mA"},
    {trigger: "@T", replacement: "\\Theta", options: "mA"},
    {trigger: "@k", replacement: "\\kappa", options: "mA"},
    {trigger: "@K", replacement: "\\kappa", options: "mA"},
    {trigger: "@l", replacement: "\\lambda", options: "mA"},
    {trigger: "@L", replacement: "\\Lambda", options: "mA"},
    {trigger: "@m", replacement: "\\mu", options: "mA"},
    {trigger: "@M", replacement: "\\mu", options: "mA"},
    {trigger: "@r", replacement: "\\rho", options: "mA"},
    {trigger: "@R", replacement: "\\rho", options: "mA"},
    {trigger: "@s", replacement: "\\sigma", options: "mA"},
    {trigger: "@S", replacement: "\\Sigma", options: "mA"},
    {trigger: "ome", replacement: "\\omega", options: "mA"},
    {trigger: "@o", replacement: "\\omega", options: "mA"},
    {trigger: "@O", replacement: "\\Omega", options: "mA"},
    {trigger: "([^\\\\])(${GREEK}|${SYMBOL}|${MACRO})", replacement: "[[0]]\\[[1]]", options: "rmA", description: "Add backslash before greek letters and symbols and macros", priority: 5},
    {trigger: "([^\\\\])(${BRACK})", replacement: "[[0]]\\[[1]]{$0}$1", options: "rmA", description: "Add backslash before brackets, with 1 brack after"},
    {trigger: "\\\\(${BRACK}){\\*", replacement: "\\[[0]]*{", options: "rmA", description: "Add star"},
    {trigger: "([^\\\\])(${INTERVAL})", replacement: "[[0]]\\[[1]]{$0}{$1}$2", options: "rmA", description: "Add backslash before intervals, with 2 bracks after", priority: 2},


    // Insert space after greek letters and symbols, etc
    {trigger: "\\\\(${GREEK}|${SYMBOL}|${SHORT_SYMBOL}|${MACRO})([A-Za-z])", replacement: "\\[[0]] [[1]]", options: "rmA", priority: 1},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) sr", replacement: "\\[[0]]^{2}", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) cb", replacement: "\\[[0]]^{3}", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) rd", replacement: "\\[[0]]^{$0}$1", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) hat", replacement: "\\hat{\\[[0]]}", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) dot", replacement: "\\dot{\\[[0]]}", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) bar", replacement: "\\bar{\\[[0]]}", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) vec", replacement: "\\vec{\\[[0]]}", options: "rmA"},
    {trigger: "\\\\(${GREEK}|${SYMBOL}) tilde", replacement: "\\tilde{\\[[0]]}", options: "rmA"},
//    {trigger: "\\\\(${GREEK}|${SYMBOL}) und", replacement: "\\underline{\\[[0]]}", options: "rmA"},
    {trigger: "\\\\(${GREEK}),\\.", replacement: "\\boldsymbol{\\[[0]]}", options: "rmA"},
    {trigger: "\\\\(${GREEK})\\.,", replacement: "\\boldsymbol{\\[[0]]}", options: "rmA"},


    // Operations
    {trigger: "te", replacement: "\\text{$0}", options: "m"},
    {trigger: "text", replacement: "\\text{$0}", options: "mA"},
    {trigger: "bf", replacement: "\\mathbf{$0}", options: "mA"},
    {trigger: "sr", replacement: "^{2}", options: "mA"},
    {trigger: "cb", replacement: "^{3}", options: "mA"},
    {trigger: "rd", replacement: "^{$0}$1", options: "mA"},
    {trigger: "_", replacement: "_{$0}$1", options: "mA"},
    {trigger: "tr", replacement: "\\transpose", options: "mA"},
    {trigger: "sts", replacement: "_\\text{$0}", options: "rmA"},
    {trigger: "sq", replacement: "\\sqrt{ $0 }$1", options: "mA"},
    {trigger: "//", replacement: "\\frac{$0}{$1}$2", options: "mA"},
    {trigger: "rm", replacement: "\\mathrm{$0}$1", options: "mA"},
    {trigger: "conj", replacement: "\\conj\{$0\}", options: "mA"},
    {trigger: "^\\topace", replacement: "\\tr", options: "mA"},
    {trigger: "det", replacement: "\\det", options: "mA"},
    {trigger: "Re", replacement: "\\mathrm{Re}", options: "mA"},
    {trigger: "Im", replacement: "\\mathrm{Im}", options: "mA"},
    {trigger: "pow", replacement: "\\power($0)$1", options: "mA"},

    {trigger: "([a-zA-Z]),\\.", replacement: "\\mathbf{[[0]]}", options: "rmA"},
    {trigger: "([a-zA-Z])\\.,", replacement: "\\mathbf{[[0]]}", options: "rmA"},
    {trigger: "([A-Za-z])([\\d])", replacement: "[[0]]_{[[1]]}", options: "rmA", description: "Auto number subscript", priority: -2},
//    {trigger: "([A-Za-z])([nij])\\2", replacement: "[[0]]_{[[1]]}", options: "rmA", description: "Auto letter subscript", priority: -1},
    {trigger: " *u([A-Za-z\\d])", replacement: "_{[[0]]}", options: "rmA", description: "Auto letter subscript", priority: -1},
    {trigger: "_\\{([A-Za-z\\d])\\}\\1", replacement: "^{[[0]]}", options: "rmA", description: "subscript to superscript", priority: -1},
    {trigger: "\\^\\{([A-Za-z\\d])\\}\\1", replacement: "_{[[0]]}", options: "rmA", description: "superscript to subscript", priority: -1},

    {trigger: "([A-Za-z])_(\\d\\d)", replacement: "[[0]]_{[[1]]}", options: "rmA"},
    {trigger: "\\hat{([A-Za-z])}(\\d)", replacement: "hat{[[0]]}_{[[1]]}", options: "rmA"},
    {trigger: "\\\\mathbf{([A-Za-z])}(\\d)", replacement: "\\mathbf{[[0]]}_{[[1]]}", options: "rmA"},
    {trigger: "\\\\vec{([A-Za-z])}(\\d)", replacement: "\\vec{[[0]]}_{[[1]]}", options: "rmA"},
    {trigger: "([a-zA-Z])bar", replacement: "\\bar{[[0]]}", options: "rmA"},
    {trigger: "([a-zA-Z])hat", replacement: "\\hat{[[0]]}", options: "rmA"},
    {trigger: "([a-zA-Z])ddot", replacement: "\\ddot{[[0]]}", options: "rmA", priority: 3},
    {trigger: "([a-zA-Z])dot", replacement: "\\dot{[[0]]}", options: "rmA", priority: 1},
    {trigger: "([a-zA-Z])vec", replacement: "\\vec{[[0]]}", options: "rmA"},
    {trigger: "([a-zA-Z])tilde", replacement: "\\tilde{[[0]]}", options: "rmA"},
    {trigger: "([a-zA-Z])und", replacement: "\\underline{[[0]]}", options: "rmA"},
    {trigger: "bar", replacement: "\\bar{$0}$1", options: "mA"},
    {trigger: "hat", replacement: "\\hat{$0}$1", options: "mA"},
    {trigger: "dot", replacement: "\\dot{$0}$1", options: "mA"},
    {trigger: "ddot", replacement: "\\ddot{$0}$1", options: "mA", priority: 2},
    {trigger: "vec", replacement: "\\vec{$0}$1", options: "mA"},
    {trigger: "tilde", replacement: "\\tilde{$0}$1", options: "mA"},
    {trigger: "und", replacement: "\\underline{$0}$1", options: "mA"},
    {trigger: "over", replacement: "\\overline{$0}$1", options: "mA"},

    {trigger: "([^\\\\])(arcsin|arccos|arctan|arccot|arccsc|arcsec|sin|cos|tan|cot|csc)", replacement: "[[0]]\\[[1]]", options: "rmA"},
    {trigger: "\\\\(arcsin|arccos|arctan|arccot|arccsc|arcsec|sin|cos|tan|cot|csc)([A-Za-gi-z])", replacement: "\\[[0]] [[1]]", options: "rmA"}, // Insert space after trig funcs. Skips letter "h" to allow sinh, cosh, etc.
    {trigger: "\\\\(arcsinh|arccosh|arctanh|arccoth|arcsch|arcsech|sinh|cosh|tanh|coth|csch)([A-Za-z])", replacement: "\\[[0]] [[1]]", options: "rmA"}, // Insert space after trig funcs
//    {trigger: "\\\\(neq|geq|leq|gg|ll|sim)([0-9]+)", replacement: "\\[[0]] [[1]]", options: "rmA"}, // Insert space after inequality symbols
    {trigger: "\\\\in([A-Za-z])", replacement: "\\in [[0]]", options: "rmA"}, // Insert space after \in

    // Visual operations
    {trigger: "U", replacement: "\\underbrace{ ${VISUAL} }_{ $0 }", options: "mA"},
    {trigger: "B", replacement: "\\underset{ $0 }{ ${VISUAL} }", options: "mA"},
    {trigger: "C", replacement: "\\cancel{ ${VISUAL} }", options: "mA"},
    {trigger: "K", replacement: "\\cancelto{ $0 }{ ${VISUAL} }", options: "mA"},
    {trigger: "S", replacement: "\\sqrt{ ${VISUAL} }", options: "mA"},



    // Symbols
    {trigger: "ooo", replacement: "\\infty", options: "mA"},
    {trigger: "sum", replacement: "\\sum", options: "mA"},
    {trigger: "prod", replacement: "\\prod", options: "mA"},
//    {trigger: "lim", replacement: "\\lim_{ ${0:n} \\to ${1:\\infty} } $2", options: "mA"},
    {trigger: "([^\\\\])pm", replacement: "[[0]]\\pm", options: "rm"},
    {trigger: "([^\\\\])mp", replacement: "[[0]]\\mp", options: "rm"},
    {trigger: "+-", replacement: "\\pm", options: "mA"},
    {trigger: "-+", replacement: "\\mp", options: "mA"},
    {trigger: "...", replacement: "\\dots", options: "mA"},
    {trigger: "<->", replacement: "\\leftrightarrow ", options: "mA"},
    {trigger: "->", replacement: "\\to", options: "mA"},
    {trigger: "!>", replacement: "\\mapsto", options: "mA"},
    {trigger: "invs", replacement: "^{-1}", options: "mA"},
    {trigger: "sm", replacement: "\\setminus", options: "mA"},
    {trigger: "comp", replacement: "^\\complement", options: "mA"},
    {trigger: "||", replacement: "\\mid", options: "mA"},
    {trigger: "inn", replacement: "\\in", options: "mA"},
    {trigger: "sub", replacement: "\\subseteq", options: "mA"},
    {trigger: "\\subseteqn", replacement: "\\subsetneq", options: "mA"},
    {trigger: "\\sup er", replacement: "\\supset", options: "mA"},
    {trigger: "\\supset eq", replacement: "\\supseteq", options: "mA"},
    //{trigger: "set", replacement: "\\{ $0 \\}$1", options: "mA"},
    {trigger: "=>", replacement: "\\implies", options: "mA"},
    {trigger: "=<", replacement: "\\impliedby", options: "mA"},
    {trigger: "iff", replacement: "\\iff", options: "mA"},
    {trigger: "e\\xi sts", replacement: "\\exists", options: "mA", priority: 1},
    {trigger: "forall", replacement: "\\forall", options: "mA", priority: 9},
    {trigger: "===", replacement: "\\equiv", options: "mA"},
    {trigger: "Sq", replacement: "\\square", options: "mA"},
    {trigger: "!=", replacement: "\\neq", options: "mA"},
    {trigger: ">=", replacement: "\\geq", options: "mA"},
    {trigger: "<=", replacement: "\\leq", options: "mA"},
    {trigger: "~~", replacement: "\\sim", options: "mA"},
    {trigger: "\\sim ~", replacement: "\\approx", options: "mA"},
    {trigger: "prop", replacement: "\\propto", options: "mA"},
    {trigger: "nabl", replacement: "\\nabla", options: "mA"},
    {trigger: "del", replacement: "\\nabla", options: "m"},
    {trigger: "xx", replacement: "\\times", options: "mA"},
    {trigger: "**", replacement: "\\cdot", options: "mA"},
    {trigger: "para", replacement: "\\parallel", options: "mA"},



    {trigger: "mcal", replacement: "\\mathcal{$0}$1", options: "mA"},
    {trigger: "msf", replacement: "\\mathsf{$0}$1", options: "mA"},
    {trigger: "mscr", replacement: "\\mathscr{$0}$1", options: "mA"},
    {trigger: "mbb", replacement: "\\mathbb{$0}$1", options: "mA"},
    {trigger: "mfrak", replacement: "\\mathfrak{$0}$1", options: "mA"},
    {trigger: "ell", replacement: "\\ell", options: "mA"},
    {trigger: "lll", replacement: "\\ell", options: "mA"},
    {trigger: "LL", replacement: "\\mathcal{L}", options: "mA"},
    {trigger: "PP", replacement: "\\mathcal{P}", options: "mA"},
    {trigger: "HH", replacement: "\\mathcal{H}", options: "mA"},
    {trigger: "CC", replacement: "\\mathbb{C}", options: "mA"},
    {trigger: "RR", replacement: "\\mathbb{R}", options: "mA"},
    {trigger: "RP", replacement: "\\mathbb{RP}", options: "mA"},
    {trigger: "ZZ", replacement: "\\mathbb{Z}", options: "mA"},
    {trigger: "NN", replacement: "\\mathbb{N}", options: "mA"},
    {trigger: "QQ", replacement: "\\mathbb{Q}", options: "mA"},
    {trigger: "FF", replacement: "\\mathbb{F}", options: "mA"},
    {trigger: "II", replacement: "\\mathbb{1}", options: "mA"},
    {trigger: "\\mathbb{1}I", replacement: "\\hat{\\mathbb{1}}", options: "mA"},
    {trigger: "AA", replacement: "\\mathcal{A}", options: "mA"},
    {trigger: "BB", replacement: "\\mathbf{B}", options: "mA"},
    {trigger: "EE", replacement: "\\mathbf{E}", options: "mA"},



    // Derivatives
    {trigger: "par", replacement: "\\frac{ \\partial ${0:y} }{ \\partial ${1:x} }$2", options: "m"},
    {trigger: "pap", replacement: "\\left.\\frac{ \\partial }{ \\partial x^{${0:i}} }\\right\\vert_{p}$2", options: "m"},
    {trigger: "paf", replacement: "\\frac{ \\partial f}{ \\partial x^{${0:i}} }$2", options: "m"},
    {trigger: "pai", replacement: "\\frac{ \\partial }{ \\partial x^{${0:i}} }$1", options: "m"},
    {trigger: "pafij", replacement: "\\frac{ \\partial ${0:F}^{i}}{ \\partial x^{j} }$2", options: "m"},
    {trigger: "jac", replacement: "\\frac{ \\partial (F^{1},\\dots,F^{n}) }{ \\partial (x^{1},\\dots,x^{n}) }$2", options: "m"},
    {trigger: "pa2", replacement: "\\frac{ \\partial^{2} ${0:y} }{ \\partial ${1:x}^{2} } $2", options: "mA"},
    {trigger: "pa3", replacement: "\\frac{ \\partial^{3} ${0:y} }{ \\partial ${1:x}^{3} } $2", options: "mA"},
//    {trigger: "pa([A-Za-z])([A-Za-z])", replacement: "\\frac{ \\partial [[0]] }{ \\partial [[1]] } ", options: "rm"},
//    {trigger: "pa([A-Za-z])([A-Za-z])([A-Za-z])", replacement: "\\frac{ \\partial^{2} [[0]] }{ \\partial [[1]] \\partial [[2]] } ", options: "rm"},
//    {trigger: "pa([A-Za-z])([A-Za-z])2", replacement: "\\frac{ \\partial^{2} [[0]] }{ \\partial [[1]]^{2} } ", options: "rmA"},
    {trigger: "de([A-Za-z])([A-Za-z])", replacement: "\\frac{ d[[0]] }{ d[[1]] } ", options: "rm"},
    {trigger: "de([A-Za-z])([A-Za-z])2", replacement: "\\frac{ d^{2}[[0]] }{ d[[1]]^{2} } ", options: "rmA"},
    {trigger: "ddt", replacement: "\\frac{d}{dt} ", options: "mA"},



    // Integrals
    {trigger: "oinf", replacement: "\\int_{0}^{\\infty} $0 \\, d${1:x} $2", options: "mA"},
    {trigger: "infi", replacement: "\\int_{-\\infty}^{\\infty} $0 \\, d${1:x} $2", options: "mA"},
    {trigger: "dint", replacement: "\\int_{${0:0}}^{${1:\\infty}} $2 \\, d${3:x} $4", options: "mA"},
    {trigger: "oint", replacement: "\\oint", options: "mA"},
    {trigger: "iiint", replacement: "\\iiint", options: "mA"},
    {trigger: "iint", replacement: "\\iint", options: "mA"},
    {trigger: "int", replacement: "\\int", options: "mA"},


    // Quantum mechanics
    {trigger: "hba", replacement: "\\hbar", options: "mA"},
    {trigger: "dag", replacement: "^{\\dagger}", options: "mA"},
    {trigger: "o+", replacement: "\\oplus ", options: "mA"},
    {trigger: "ox", replacement: "\\otimes ", options: "mA"},
    {trigger: "ot\\mathrm{Im}es", replacement: "\\otimes ", options: "mA"}, // Handle conflict with "im" snippet
    {trigger: "bra", replacement: "\\bra{$0} $1", options: "mA"},
    {trigger: "ket", replacement: "\\ket{$0} $1", options: "mA"},
    {trigger: "brk", replacement: "\\braket{ $0 | $1 } $2", options: "mA"},
    {trigger: "\\\\bra{([^|]+)\\|", replacement: "\\braket{ [[0]] | $0 ", options: "rmA", description: "Convert bra into braket"},
    {trigger: "\\\\bra{(.+)}([^ ]+)>", replacement: "\\braket{ [[0]] | $0 ", options: "rmA", description: "Convert bra into braket (alternate)"},
    {trigger: "outp", replacement: "\\ket{${0:\\psi}} \\bra{${0:\\psi}} $1", options: "mA"},



    // Environments
    {trigger: "pmat", replacement: "\\begin{pmatrix}\n$0\n\\end{pmatrix}", options: "mA"},
    {trigger: "bmat", replacement: "\\begin{bmatrix}\n$0\n\\end{bmatrix}", options: "mA"},
    {trigger: "Bmat", replacement: "\\begin{Bmatrix}\n$0\n\\end{Bmatrix}", options: "mA"},
    {trigger: "vmat", replacement: "\\begin{vmatrix}\n$0\n\\end{vmatrix}", options: "mA"},
    {trigger: "Vmat", replacement: "\\begin{Vmatrix}\n$0\n\\end{Vmatrix}", options: "mA"},
    {trigger: "case", replacement: "\\begin{cases}\n$0\n\\end{cases}", options: "mA"},
    {trigger: "align", replacement: "\\begin{align}\n$0\n\\end{align}", options: "mA"},
    {trigger: "array", replacement: "\\begin{array}\n$0\n\\end{array}", options: "mA"},
    {trigger: "matrix", replacement: "\\begin{matrix}\n$0\n\\end{matrix}", options: "mA"},



    // Brackets
    {trigger: "avg", replacement: "\\langle $0 \\rangle $1", options: "mA"},
    {trigger: "norm", replacement: "\\norm\{$0\}", options: "mA", priority: 1},
    {trigger: "mod", replacement: "\\mod", options: "mA"},
    {trigger: "(", replacement: "(${VISUAL})", options: "mA"},
    {trigger: "[", replacement: "[${VISUAL}]", options: "mA"},
    {trigger: "{", replacement: "{${VISUAL}}", options: "mA"},
    {trigger: "(", replacement: "($0)$1", options: "mA"},
    {trigger: "{", replacement: "{$0}$1", options: "mA"},
    {trigger: "[", replacement: "[$0]$1", options: "mA"},
    {trigger: "lr(", replacement: "\\left( $0 \\right) $1", options: "mA"},
    {trigger: "lr|", replacement: "\\left| $0 \\right| $1", options: "mA"},
    {trigger: "lr{", replacement: "\\left\\{ $0 \\right\\} $1", options: "mA"},
    {trigger: "lr[", replacement: "\\left[ $0 \\right] $1", options: "mA"},
    {trigger: "lra", replacement: "\\left< $0 \\right> $1", options: "mA"},



    // Misc
    {trigger: "tayl", replacement: "${0:f}(${1:x} + ${2:h}) = ${0:f}(${1:x}) + ${0:f}'(${1:x})${2:h} + ${0:f}''(${1:x}) \\frac{${2:h}^{2}}{2!} + \\dots$3", options: "mA"},
    {trigger: "\\\\(int|sum|prod)", replacement: "\\[[0]]_{$0}^{$1}$2", options: "rm"},

]

/*
```
*/