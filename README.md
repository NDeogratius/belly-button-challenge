# Module 14 Challenge: Belly Button Biodiversity Dashboard

## Background
The purpose of this challenge is to build an interactive dashboard that explores the Belly Button Biodiversity dataset. This dataset catalogs the microbes that colonize human navels, revealing that a small handful of microbial species (referred to as operational taxonomic units, or OTUs) are present in more than 70% of people, while the remaining species are relatively rare.

## Repository Setup

1. **Create a New Repository:**
   - A new GitHub repository named `belly-button-challenge` was created for this project.
   - The repository was then cloned to the local machine.

2. **File Setup:**
   - The files from the `StarterCode` folder provided within the Module 14 Challenge zip file, including `index.html`, `samples.json`, and the `static` folder, were copied into the local repository.
   - Although the `samples.json` file is provided, it is not accessed locally; rather, the data is accessed via a URL.
   - All initial changes were committed and pushed to GitHub.

3. **Deployment:**
   - The repository was deployed to GitHub Pages, enabling the interactive dashboard to be hosted online.

## Instructions & Tasks

### 1. Data Retrieval with D3
- **Objective:** Use the D3 library to load the `samples.json` data from the URL: `https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json`.

### 2. Horizontal Bar Chart
- **Objective:** Create a horizontal bar chart that visualizes the top 10 OTUs found in a selected individual.
   - **Values:** `sample_values` were used as the values for the bar chart.
   - **Labels:** `otu_ids` were used as the labels for the bar chart.
   - **Hovertext:** `otu_labels` were used as the hovertext for the bar chart.

### 3. Bubble Chart
- **Objective:** Create a bubble chart that displays each sample's data.
   - **X Values:** `otu_ids` were used for the x-axis values.
   - **Y Values:** `sample_values` were used for the y-axis values.
   - **Marker Size:** `sample_values` were used to determine the size of the markers.
   - **Marker Colors:** `otu_ids` were used to determine the color of the markers.
   - **Text Values:** `otu_labels` were used for the text values that appear when hovering over the bubbles.

### 4. Sample Metadata Display
- **Objective:** Display the demographic information of an individual.
   - Each key-value pair from the metadata JSON object was looped through and appended as an HTML tag to the `#sample-metadata` panel.

### 5. Interactive Dashboard
- **Objective:** Ensure that all plots and the metadata display are updated when a new sample is selected from the dropdown menu.

### 6. Deployment
- **Objective:** Deploy the completed app to a static page hosting service, such as GitHub Pages.
   - The links to both the GitHub repository and the deployed dashboard were submitted as part of the challenge requirements.

## Final Outcome

The interactive dashboard successfully visualizes the microbial data from the Belly Button Biodiversity dataset. Users can explore the data by selecting different individuals from a dropdown menu, which dynamically updates the bar chart, bubble chart, and demographic information displayed on the dashboard.

## Links
- **GitHub Repository:** [belly-button-challenge](https://github.com/NDeogratius/belly-button-challenge)
- **Deployed Dashboard:** [GitHub Pages Deployment](https://ndeogratius.github.io/belly-button-challenge/)

