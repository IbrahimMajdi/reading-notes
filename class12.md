## chart js
>Chart js is a free open-source JavaScript library for data visualization.

>Chart js have a great documentation to 

~~~~
<canvas id="chart" width="100" height="100"></canvas>
~~~~

> `<canvas>` tag acts like a container for the chart js code.
> `<canvas>`only supports two primitive shapes: rectangles and paths.

> with canvas you can draw on the webpage things similar to what you can do using graphic design programs.

>some drawing commands for canvas  

> to draws a filled rectangle.
~~~~
fillRect(x, y, width, height)
~~~~

>Draws a solid shape by filling the path's content area.
~~~~
fill()
~~~~

>Draws a line from the current drawing position to the position specified by x and y. 
~~~~
lineTo(x, y)
~~~~

> Sets the style used when filling shapes.
~~~~
fillStyle = color
~~~~

>Sets the style for shapes' outlines
~~~~
strokeStyle = color
~~~~

>Applies the specified transparency value to all future shapes drawn on the canvas
~~~~
globalAlpha = transparencyValue
~~~~

>Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
~~~~
fillText(text, x, y [, maxWidth])
~~~~
