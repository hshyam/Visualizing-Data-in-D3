Harshita Shyam

Design: The first part of my design is a line graph for “World Population.” I started of by writing code to create a line in the line graph. The x-axis is the current year and the y-axis is the worlds population over the years 1950 to 2049. The d3.scale.linear function constructs a new linear scale. Then, I used the xScale function to map the year data into the graph’s x-range and the yScale function to map the world population data into the graph’s y-range. Next, I implemented the d3.svg.line function to create a line generator that reflects the trajectory of the data and then added the line to the SVG element.

Then, I created the d3.axis function for the x-axis and y-axis with five tick marks and tick label. Here, we see that the y-axis reflects the world population and the x-axis reflects the current year. For the x-axis, the format function is implemented so that there is no comma. Next, the axes are added to the SVG element called chart. Then, we draw a title label on the top-middle of the graph.

The second part of my design is a bar graph for the “Annual Population Change.” Here, I reused most of the code that was used to draw the line graph from the previous section. The x-axis remains as the current year while the y-axis now represents the annual population change data. Then, i modified the line generator part of the code to draw bars instead of lines. Then, I changed the title label of the graph to “Annual Population Change” which is in the top middle of the graph.

In the final part of the assignment, I implemented some additional features: 

The first feature is coloring the bars in the bar graph. I created a variable called colors that is set up to be d3.scale.linear(). I set up the bars to be blue in color separated by white which gives it a dimensional affect making it easier to read and understand. 

The second feature is adding events. I added an event on mouseover that fills the bars that are selected in the graph with yellow and on mouseout, it fills the bars with gray.This makes it easier to visualize a certain data point such as the annual population change over a given year.

The third feature is adding an animation. Here, I implemented transition function with a delay in duration so that when it is used for presentation purposes, one can hover the mouse over the bar graph and can show all the bars/data that can either be shown as a single entity or a group. I’ve set the delay in duration to a longer time so that one can see it clearly being shown.



