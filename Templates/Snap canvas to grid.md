<%*
thing = await tp.system.prompt("Paste canvas file here", "", true, true);

thing = thing.replace(/:-?\d+/g, n => ":"+Math.round(n.slice(1)/20)*20)


console.log(thing);
%>