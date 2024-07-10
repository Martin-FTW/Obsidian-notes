<%* 
snippet = await tp.system.prompt("LaTeX snippet:", "https://tikzcd.yichuanshen.de/", true, true); 
commands = "\\newcommand\\mfbox[1]{\\fbox{\\begin{tabular}{@{}c@{}}#1\\end{tabular}}}"
tR += "```tikz\n" + 
"\\usepackage{tikz-cd}\n" + 
"\\usepackage{amsmath}\n" + 
"\\usepackage{amsfonts}\n" + 
"\\newcommand\\mfbox[1]{\\fbox{\\begin{tabular}{@{}c@{}}#1\\end{tabular}}}" + 
"\\newcommand\\mmbox[1]{\\mbox{\\begin{tabular}{@{}c@{}}#1\\end{tabular}}}" + 
"\n\\begin{document}\n" + 
snippet.replace(/\s\s+/g, ' ').replace(/no head, Rightarrow/g, "Leftrightarrow") + 
"\n\\end{document}\n```"
%>