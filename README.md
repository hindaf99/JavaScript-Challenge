
# Plot.ly Homework - Belly Button Biodiversity

![image](https://user-images.githubusercontent.com/83431185/145314846-167b287b-0e73-4da6-b4ad-3e2c64afc8da.png)

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly


1. Use the D3 library to read in samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

- Use sample_values as the values for the bar chart.

- Use otu_ids as the labels for the bar chart.

- Use otu_labels as the hovertext for the chart.

![image](https://user-images.githubusercontent.com/83431185/145314860-037b1d18-db91-41e9-9374-801d8d1f8b28.png)



3. Create a bubble chart that displays each sample.



- Use otu_ids for the x values.

- Use sample_values for the y values.

- Use sample_values for the marker size.

- Use otu_ids for the marker colors.

- Use otu_labels for the text values.

![image](https://user-images.githubusercontent.com/83431185/145314912-5ff3ccad-dfb2-40d5-9f5d-bea1d06adbc2.png)


4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/83431185/145314954-90949997-be08-4c48-ad18-528dca1e59a8.png)

6. Update all of the plots any time that a new sample is selected.

Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:
![image](https://user-images.githubusercontent.com/83431185/145314985-01165c7a-3cb1-4a71-9144-ba25f96ff9fd.png)

