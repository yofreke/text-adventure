'Living room', 'A dusty and old yet lavish livig space seemingly untouched for decades sets before you. There is furniture dotted about, a couch a {ITEM:painting} above the fireplace, as well as a small {ITEM:chest} beside the fireplace. On the other side of the fireplace you see an old iron supported door, though there is no indication of as to where the door leads.

``` js
var marked = require('marked');
var TerminalRenderer = require('marked-terminal');

marked.setOptions({
  // Define custom renderer
  renderer: new TerminalRenderer()
});

//
console.log(marked(livingRoomDesc));