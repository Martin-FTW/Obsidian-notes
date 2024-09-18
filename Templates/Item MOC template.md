<%* 
const lines = app.workspace.activeLeaf.view.editor.getCursor().line;
let content = tp.file.content.split('\n').slice(0, lines+1);
content = content.map(e=>e.replace(/=/g,""))
let title = content[0].split(" ");
title = title[title.length-1].replace(/[()]/g, "").replace("MATH", "");
const names = new Map([
	["D", "Definition"],
	["P", "Proposition"],
	["T", "Theorem"],
	["L", "Lemma"],
	["C", "Corollary"],
	["Cl", "Claim"],
	["R", "Remark"],
	["Eg", "Example"],
	["Ex", "Exercise"],
	["Ep", "Exposition"],
	["Pb", "Problem"],
	["J", "Joke"],
	["A", "Axiom"],
	["N", "Notation"],
])
const type = await tp.system.suggester((item) => ["Pb", "Cl"].includes(item) ? "_"+item+": "+names.get(item) : item+": "+names.get(item), Array.from(names.keys()));

// Find chapter and section number
const chapter = content.findLast((element)=>element.startsWith("## ")).split(" ")[1];
let section = content.findLast((element)=>element.startsWith("### "));
// Change according to tags
section = (section == undefined || (tp.file.tags.includes("#nonumsec") && type != "Eg" && type != "Pb")) ? "" : section.split(" ")[1];
let lastsec = content.findLastIndex((element)=>tp.file.tags.includes("#nonumsec") ? element.startsWith("## ") : element.startsWith("#"));
temp = content.slice(lastsec)
let lastline = content.slice(lastsec).findLast(e=>e.startsWith("- [[")&&(e.match(/\d]]/)||e.match(/\d \(/)))
lastline = (lastline == undefined) ? "" : lastline
let lastnum = lastline.match(/\.(\w+)[\]\s]/g)
lastnum = (lastnum === null) ? "0" : lastnum[0].slice(1,-1)
console.log(lastnum)
lastnum = (tp.file.tags.includes("#nonum")&&type!="Eg"&&type!="Pb")||(tp.file.tags.includes("#nonumdef")&&type=="D") ? "" : lastnum - "-1"; 
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
tp.file.cursor_append(`\n- [[${title} ${type} ${output}]]`);
await tp.file.create_new(`Book: [[${tp.file.title}]]
# ${names.get(type)} ${output}
${tp.file.cursor(1)}`, `${title} ${type} ${output}`, true, `Math brain/${tp.file.title}`);
%>