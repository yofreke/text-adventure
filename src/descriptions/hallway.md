'Hallway', 'As you walk through the eastern doorway of the fower you find yourself in a long dimly lit hallway stands before you, very little light shines in from the outside through the windows and the only viable source is the candles that sit upon window seals, it is unnerving though as the candles seem to have only been lit recently. You are not alone it seems. Down the  hallway of many sealed doors only two are cracked open, the first door on the right and the second to last door on the left '


``` js
var marked = require('marked');
var TerminalRenderer = require('marked-terminal');

marked.setOptions({
  // Define custom renderer
  renderer: new TerminalRenderer()
});

// Show the parsed data
console.log(marked(hallwayDesc);
```