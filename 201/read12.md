# Chart

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

## ChartJs
 *Chart.js*, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

 - Chart.js is available under the MIT license

 - Creating a Chart :
 
    To create a chart, we need to instantiate the ```Chart``` class

     we need to pass r 2d context of the canvas of where we want to draw the chart .

     ```var ctx = document.getElementById('myChart');```