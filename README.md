# belly-button-challenge

## Background
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Website Link

[Belly Button Biodiversity Dashboard](https://jonkwiatkowski.github.io/Biodiversity-Dashboard/)

## Outline

Completed the following steps:

1. Used the D3 library to read in `samples.json` from the URL `https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json`.

2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual. The chart used the following:

  *  `sample_values` as the values for the bar chart.

  *  `otu_ids` as the labels for the bar chart.

  *  `otu_labels` as the hovertext for the chart.

3. Created a bubble chart that displays each sample. The chart used the following:

  * `otu_ids` for the x values.

  * `sample_values` for the y values.

  * `sample_values` for the marker size.

  * `otu_ids` for the marker colors.

  * `otu_labels` for the text values.

4. Displayed the sample metadata, i.e., an individual's demographic information.

5. Displayed each key-value pair from the metadata JSON object somewhere on the page.

6. Updated all the plots when a new sample is selected. 

7. Deployed the app to GitHub Pages.


## References

* Homework 14 Instructions

* Dom LaBella, Homework 14 Tutorial

* Hulcr, J. et al. (2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

