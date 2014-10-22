snap.multiline.js
=================

A plugin for the [Snap.svg](http://github.com/adobe-webplatform/Snap.svg) library that adds the ability for newlines in text elements.

snap.multiline.js is licensed under the terms of the MIT License.

## Introduction
Since SVG does not support newlines, they must be simulated by creating separate text elements for each line of text. This provides a way to do it with \n as in Javascript.

## Usage
Include this plugin after including the Snap.svg.js library in your html document.

To enable text with newlines:

```javascript
Snap("svg").multitext(100, 100, "Sample\nmultiline\ntext").attr({
    font: "30px Nautilus Pompilius",
    textAnchor: "middle"
});
```

