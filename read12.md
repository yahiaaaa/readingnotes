# Chart.js 


![image text](https://cdn.mos.cms.futurecdn.net/S5bicwPe8vbP9nt3iwAwwi-1024-80.jpg.webp "image Title")

What is a Chart.js ?

its a way to draw graph onto the html page using HTML5’s canvas element.

Setting up
download Chart.js.

Copy the Chart.min.js out of the unzipped folder

Then create a new html page and import the script like this :

<!DOCTYPE html>

<html lang="en">
  
    <head>
      
        <meta charset="utf-8" />
      
        <title>Chart.js demo</title>
      
        <script src='Chart.min.js'></script>
      
    </head>
  
    <body>
      
    </body>
  
</html>

Drawing a line chart To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.

Drawing a pie chart Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:

Drawing a bar chart Finally, let’s add a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:

And finally, we add in the bar chart’s data:
var barData = { labels : [“January”,”February”,”March”,”April”,”May”,”June”], datasets : [ { fillColor : “#48A497”, strokeColor : “#48A4D1”, data : [456,479,324,569,702,600] }, { fillColor : “rgba(73,188,170,0.4)”, strokeColor : “rgba(72,174,209,0.4)”, data : [364,504,605,400,345,320] }

# Applying styles and colors

In the chapter about drawing shapes, we used only the default line and fill styles. Here we will explore the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.
Transparency
In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

Shadows
-Using shadows involves just four properties:

shadowOffsetX = float Indicates the horizontal distance the shadow should extend from the object. This value isn’t affected by the transformation matrix. The 2. default is 0.
shadowOffsetY = float Indicates the vertical distance the shadow should extend from the object. This value isn’t affected by the transformation matrix. The 3. default is 0.
shadowBlur = float Indicates the size of the blurring effect; this value doesn’t correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0.
shadowColor = color A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black.
