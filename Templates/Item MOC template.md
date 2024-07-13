<%* 
const lines = app.workspace.activeLeaf.view.editor.getCursor().line;
let content = tp.file.content.split('\n').slice(0, lines+1);
content = content.map(e=>e.replace(/=/g,""))
let title = content[0].split(" ");
title = title[title.length-1].replace(/[()]/g, "").replace("MATH", "");
const type = await tp.system.suggester((item) => item, ["Definition", "Lemma", "Proposition", "Theorem", "Corollary", "Remark", "Example", "Exercise", "Joke", "Axiom"]);
let typeletter = type.at(0);
if (type == "Example") typeletter += "g"
if (type == "Exercise") typeletter += "x"
// Find chapter and section number
const chapter = content.findLast((element)=>element.startsWith("## ")).split(" ")[1];
let section = content.findLast((element)=>element.startsWith("### "));
// Change according to tags
section = (section == undefined || (tp.file.tags.includes("#nonumsec") && type != "Exercise")) ? "" : section.split(" ")[1];
let lastsec = content.findLastIndex((element)=>tp.file.tags.includes("#nonumsec") ? element.startsWith("## ") : element.startsWith("#"));
temp = content.slice(lastsec)
let lastline = content.slice(lastsec).findLast(e=>e.startsWith("- [[")&&(e.match(/\d]]/)||e.match(/\d \(/)))
lastline = (lastline == undefined) ? "" : lastline
let lastnum = lastline.match(/\.(\w+)[\]\s]/g)
lastnum = (lastnum === null) ? "0" : lastnum[0].slice(1,-1)
console.log(lastnum)
lastnum = (tp.file.tags.includes("#nonum")&&type!="Exercise")||(tp.file.tags.includes("#nonumdef")&&type=="Definition") ? "" : lastnum - "-1"; 
const num = await tp.system.prompt("Number or name:", `${lastnum}`, true);
let output = ""

if (isNaN(num)) output += "(" + num + ")";
else {
	const name = await tp.system.prompt("Optional name:", "", true);
	output = tp.file.tags.includes("#nonumch") ? "" : chapter + ".";
	if (section != "") output += section + ".";
	output += num;
	if (name != "") output += " (" + name + ")";
}
tp.file.cursor_append(`\n- [[${title} ${typeletter} ${output}]]`);
await tp.file.create_new(`Book: [[${tp.file.title}]]
# ${type} ${output}
${tp.file.cursor(1)}`, `${title} ${typeletter} ${output}`, true);
%>