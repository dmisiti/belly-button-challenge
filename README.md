# Module 14 Challenge - JavaScript and D3

In this challenge, JavaScript was utilized to build an interactive dashboard exploring the Belly Button Biodiversity dataset.

First, the D3 library was used to read in the data from `samples.json`.

Then, two types of charts were generated using Plotly -- a bubble chart, and a horizontal bar chart.
- The bubble chart shows the type and number of bacteria present in a given sample.
- The bar chart shows the 10 most abundantly found bacteria present in a given sample.

Additionally, the demographic information of the individual being sampled was displayed alongside the two charts.

In the end, the dashboard displays a dropdown that allows a user to select any sample ID, and view the summary of information about that sample (bubble chart, bar chart, and demographic info).

The JavaScript file for this dashboard creation `app.js` is found in the "static/js" folder.

The app displaying the dashboard is found in the `index.html` file.
