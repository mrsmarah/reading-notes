**`Chart.js,`**

JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

**Setting up**

- download Chart.js./github 
- Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in
- create a new html page and import the script in it (in the link.)

**Drawing a line chart**

- create a canvas element in our HTML in which Chart.js can draw our chart
- add this to the body of our HTML page:
`<canvas id="buyers" width="600" height="400"></canvas>`
- write a script in the foot of your body elementthat will retrieve the context of the canvas`.....new Chart(buyers).Line(buyerData);`
-Now it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

**Drawing a pie chart**

- create a canvas element in our HTML in which Chart.js can draw our chart
- add this to the body of our HTML page:
`<canvas id="buyers" width="600" height="400"></canvas>`
- write a script in the foot of your body elementthat will retrieve the context of the canvas`.....new Chart(countries).Pie(pieData, pieOptions);`
- Now supply a value and a color for each section
- After the pieData we’ll add our options

**Drawing a bar chart**

- create a canvas element in our HTML in which Chart.js can draw our chart
- add this to the body of our HTML page:
`<canvas id="buyers" width="600" height="400"></canvas>`
- write a script in the foot of your body elementthat will retrieve the context of the canvas`.....new Chart(income).Bar(barData);`
- add labels for the base of our chart and datasets to describe the values on the chart.


**The `<canvas>` element**

looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height.

*It is always a good idea to supply an id because this makes it much easier to identify it in a script.*

**Fallback content**

Define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

*insert the alternate content inside the `<canvas>` element. Browsers that don't support `<canvas>` will ignore the container and render the fallback content inside it. Browsers that do support `<canvas>` will ignore the content inside the container, and just render the canvas normally.*

**The rendering context**

 The` <canvas>` element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context. For 2D graphics, such as those covered by this tutorial, you specify "2d" to get a CanvasRenderingContext2D.