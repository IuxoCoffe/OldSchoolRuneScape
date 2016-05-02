ProgressBasedRpg
================
It is a game that you play where you level up and discover things.

[It can be found here](http://j0ecool.github.io/OSTM)

cheat:
http://jsfiddle.net/HMP6T/

1.html:
<h2 id="a"></h2>
<h2 id="b"></h2>
<h2 id="c"></h2>

2.js

var a = LZString.compressToBase64('..saved_game_modified');
var b = LZString.decompressFromBase64('..saved_game_original');
var c = btoa(JSON.stringify(myArray));





$('#b').text("decompressed (orignal): " +b);

$('#a').text("compressed (modified): " +a);

