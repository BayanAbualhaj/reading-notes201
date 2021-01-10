# Read 12

## JavaScripts

### charts 

* creating charts in JS: 
1. setting up :we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. 

2. Drawing a line chart :To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.

3. Drawing a pie chart :
- First, we need the canvas element.
- we need to get the context and to instantiate the chart
- Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section
- add options :These options do two things, first they remove the stroke from the segments, and then they animate the scale of the pie so that it zooms out from nothing.

4. Drawing a bar chart:
-  add the canvas element
- we retrieve the element and create the graph
- we retrieve the element and create the graph

***The canvas element***
- has only 2 attributes **width and height** 
- not all browsers supports the canvas element
- in has an opening and closing tag 


**we use canvas tag for drawing**
- make grids 
- rectangular shape 
- creat a paths 
- drawing a triangle
- moving pen 
- lines
- arcs
- Bezier and quadratic curves
- Quadratic Bezier curves
- Cubic Bezier curves
- Making combinations


*** for applying styles and colors: ***

**colors :** 
there are two important properties we can use: 
1. fillStyle
2. strokeStyle.

**Drawing text** :
The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

*styling text*:
measureText()
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.
The following code snippet shows how you can measure a text and get its width.

