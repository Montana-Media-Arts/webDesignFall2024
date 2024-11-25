---
title: HTML5 Draw Images
module: topic-13
permalink: /topic-13/html5-draw-images/
categories: development
tags:
---

Finally, we can also work with images and make those appear on the canvas as well. Remember, the idea behind the canvas is that we have much more control.  Notice that the second and third parameters in the `drawImage` function are the x-coordinate and the y-coordinate.  Therefore, we can put it where we want on the page.  

```js
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
var img = document.getElementById("scream");
ctx.drawImage(img, 10, 10);
```
