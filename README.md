# Recency Frequency and Monetary analysis in Python using access to BigQuery and prompt user for time range selection

## Project Description

Create reusable Python code to provide Segmentation and RFM analysis of the “rfm” data table hosted in BigQuery project.

Apply date range selection for analysis as a user prompt for the required period for analysis. When the "rfm" table is updated or incremented with new periods, the user should be able to select dates for analysis within the current data in the dataset.

For the selected date range, the code provides:

  •	calculation of recency, frequency and monetary values
  
  •	visualization of recency, frequency and monetary values distribution (boxplots, histograms)
  
  •	transformation of these values into R, F and M scores using quartiles or custom cutoffs, according to the most appropriate approach based on the data distribution
  
  •	application of Segments based on the calculated RFM score
  
  •	data visualizations, allowing the user to make own insights

## About Segmentation and RFM analysis

Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately. 
Segmentation allows marketers to better tailor their marketing efforts to various audience subsets. Those efforts can relate to both communications and product development. 
Specifically, segmentation helps a company:

- Create and communicate targeted marketing messages that will resonate with specific groups of customers, but not with others (who will receive messages tailored to their needs and interests, instead)

- Select the best communication channel for the segment, which might be email, social media posts, radio advertising, or another approach, depending on the segment
  
- Identify ways to improve products or new product or service opportunities

- Establish better customer relationships
  
- Test pricing options
  
- Focus on the most profitable customers
  
- Improve customer service
  
- Upsell and cross-sell other products and services

## About the dataset

The rfm table is hosted in BigQuery project. It contains information on customer transactions, including their ID, purchase dates, quantity, and monetary value.

The dataset contains 541.909 rows and 8 columns.

**rfm schema**

| Field name | Type | Mode |
|---------------|-----------|-----------|
| InvoiceNo | STRING | NULLABLE |
| StockCode | STRING | NULLABLE |
| Description | STRING | NULLABLE |
| Quantity | INTEGER | NULLABLE |
| InvoiceDate | TIMESTAMP | NULLABLE |	
| UnitPrice | FLOAT | NULLABLE |
| CustomerID | INTEGER | NULLABLE |
| Country | STRING | NULLABLE	|


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

