# belly-button-challenge

# belly-button-challenge

Description
This project is an interactive dashboard designed to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The goal is to provide an intuitive and accessible visualization of the data to better understand microbial diversity in different individuals.

Contents
index.html: The main HTML file that structures the dashboard.
static/js/app.js: JavaScript file containing functions to read data, build charts, and update the dashboard.
samples.json: Dataset with information about the samples, metadata, and sample values.
README.md: This file, providing an overview of the project.
Usage
Open the index.html file in your preferred web browser. Interact with the dashboard by selecting different sample IDs from the dropdown menu. The charts and demographic information will automatically update based on the selected sample.

Features
Horizontal Bar Chart: Displays the top 10 OTUs found in the selected sample.
Bubble Chart: Displays all bacterial cultures per sample.
Metadata Panel: Shows the demographic information of the selected individual.
Dropdown Menu: Allows selection of different samples to update the charts and metadata panel.
Example Usage
Select a sample ID from the dropdown menu. Observe how the charts and metadata panel update with the new information. Explore different samples to compare microbial diversity between individuals.

In this project, ChatGPT was utilized to generate specific parts of the code and to debug and optimize the code's functionality. For instance, the following code snippet, which loops through each key-value pair in the metadata JSON object and appends a new HTML tag with the corresponding text to the #sample-metadata panel, was generated with the assistance of ChatGPT:

javascript
Copiar código
Object.entries(result).forEach(([key, value]) => {
  PANEL.append("h6").text(`${key.toUpperCase()}: ${value}`);
});
This helped in efficiently displaying the demographic information of the selected individual in a structured format.

OpenAi. (n.d.). ChatGPT by OpenAi from https://openai.com/chatgpt