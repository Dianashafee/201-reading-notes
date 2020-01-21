# Reading Assignment 12
## [Article: Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
- Charts are better for displaying data than tables.
  - Convey data quickly
  - Not always easy to create
- Chart.js
  - Javascript plugin that uses html canvas element to draw graphs on a page
    - Bar charts, line charts, pie charts, etc are very easy
  - Going to show examples
    - Number of buyers of fictional product over 6 months
      - Line chart
    - Which countries customers come from
      - Pie chart
    - Profit over the period
      - Bar chart
  - Download, install, and use
    - copy Chart.min.js into working directory
    - Add script to html in head: `<script src='Chart.min.js'></script>
  - Create line chart: 
    - Add `<canvas>` element to html
    - Add another script to bottom of html body: `<script> var buyers = document.getElementById('buyers').getContext('2d'); 
                                                  new Chart(buyers).Line(buyerData); </script>`
    - Inside script we need to create our data
      - This case: object that contains labels for the base of our chart and datasets to describe the values on the chart
      - Add script shown to html above var buyers
        - Adds labels for jan-june
        - Has colors and data
  - Create pie chart:
    - create canvas
    - add script: `var countries= document.getElementById("countries").getContext("2d");
                    new Chart(countries).Pie(pieData, pieOptions);`
    - This time, options available
    - Add data object, which includes values and colors for each pie slice
    - Add options object
    
  - Create bar chart:
  - create canvas
  - Add script: `var income = document.getElementById("income").getContext("2d");
                  new Chart(income).Bar(barData);`
  - Add barData object, which includes jan-june labels, colors, and data
  
## Articles: Basic Usage of Canvas, Drawing Shapes with Canvas, Applying Styles and Colors, Drawing Text
- `<canvas>` elements have height and width
- Include fallback content in-between opening and closing tags
- closing tag required
- create draw function that gets "context" of canvas with canvas.getContext
- canvas has grid coordinate system
  - origin upper left
- canvas only supports rectangles and paths
- moveTo() to "move the pen"
- Can do lines, arcs, bezier curves, quadratic curves, etc
- Can do fill and stroke colors, including transparency
- Drawing text
    
