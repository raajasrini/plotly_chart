# Plotly Chart - Belly Button Biodiversity

## Project Overview :
The aim of the project is to build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Results

### Horizontal Bar Chart :
* Use the D3 library to read in samples.json.

* Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

   * Use sample_values as the values for the bar chart.

   * Use otu_ids as the labels for the bar chart.

   * Use otu_labels as the hovertext for the chart.
   
![Horizontal Bar Chart](https://github.com/raajasrini/plotly_chart/blob/main/references/1.png)

### Bubble Chart 

* Use otu_ids for the x values.

* Use sample_values for the y values.

* Use sample_values for the marker size.

* Use otu_ids for the marker colors.

* Use otu_labels for the text values.

* Display the sample metadata, i.e., an individual's demographic information.

* Display each key-value pair from the metadata JSON object somewhere on the page.

![Bubble Chart](https://github.com/raajasrini/plotly_chart/blob/main/references/2.png)

### Gauge Chart 
* Create a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

* Created a title for the chart.

* Created the ranges for the gauge in increments of two, with a different color for each increment.

* Adds the washing frequency value on the gauge chart.

* The indicator shows the level for the washing frequency on the gauge.

* The gauge is added to the dashboard.

* The gauge fits in the margin of the div element.

![Gauge Chart](https://github.com/raajasrini/plotly_chart/blob/main/references/3.png)


### Customize the Dashboard

![Gauge Chart](https://github.com/raajasrini/plotly_chart/blob/main/references/4.png)

* Added an image to the jumbotron.

* Added background color or a variety of compatible colors to the webpage.

* Use a custom font with contrast for the colors.

* Add more information about the project as a paragraph on the page.

* Add information about what each graph visualizes, either under or next to each graph.

* Make the webpage mobile-responsive.

* Change the layout of the page.

* Add a navigation bar that allows you to select the bar or bubble chart on the page.

![Gauge Chart](https://github.com/raajasrini/plotly_chart/blob/main/references/5.png)


