### ss.js // ß.js
Imaging you want to write German words like Straße but you don't have the `ß` character on your keybord. Those times are
over with ß.js.
ß.js will automatically turn all ss into ß. You can see the replaced stuff below.

#### Usage:
```
// Include ss.js

var before = 'I live in the Musterstrasse in a town called Gross-Zimmern',
    after = ß(before);

console.log(after);
// => 'I live in the Musterstraße in a town called Groß-Zimmern'.
```
For speed and performance there's also a minified version of the script called ß.min.js.
There's a working example over at [CodePen](http://codepen.io/kevingimbel/pen/nkdpD)
