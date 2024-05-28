# Recency Frequency and Monetary analysis in Python using access to BigQuery and prompt user for time range selection

## Project Description:

Create reusable Python code to provide Segmentation and RFM analysis of the “rfm” data table hosted in BigQuery project.

Apply date range selection for analysis as a user prompt for the required period for analysis. When the "rfm" table is updated or incremented with new periods, the user should be able to select dates for analysis within the current data in the dataset.

For the selected date range, the code provides:

  •	calculation of recency, frequency and monetary values
  
  •	visualization of recency, frequency and monetary values distribution (boxplots, histograms)
  
  •	transformation of these values into R, F and M scores using quartiles or custom cutoffs, according to the most appropriate approach based on the data distribution
  
  •	application of Segments based on the calculated RFM score
  
  •	data visualizations, allowing the user to make own insights

## Steps applied

Step 1. Importing data from Big Query to Google Colab

Step 2. Exploratory data analysis

Step 3. Cleaning data set for further analysis

Step 4. Selecting date range for analysis by user prompt

Step 5. Calculating recency, frequency and monetary

Step 6. Visualization of recency, frequency and monetary values distribution

Step 7. Applying RFM score

Step 8. Defining Segments

Step 9. RFM analysis and visualization

## Access to the project
The project has been prepared in Google Colab. The visuals in the project have been prepared using plotly.express and were saved as images in the uploaded file. The initial version of the project can be found [here]( https://colab.research.google.com/drive/17qupcY8R4R9xrGV-vfLO3IkzENeMcYc1)

