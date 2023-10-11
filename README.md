# RFM Analysis (Customer segmentation)

![RFM Analysis](https://github.com/M0hamedIbrahim1/RFM-Analysis/blob/main/Dataset/rfm1.png)

## Introduction

This project implements RFM (Recency, Frequency, Monetary) analysis to segment customers and identify opportunities for targeted marketing campaigns. RFM analysis is a powerful technique used by companies to better understand customer behavior and optimize engagement strategies. It revolves around three key dimensions: recency, frequency, and monetary value, which are essential aspects of customer transactions and provide valuable information for segmentation and personalized marketing campaigns. Visualizations are an integral part of presenting the insights gained from these analyses.

## Methodology

The following steps were used to implement RFM analysis:

- **Calculate Recency & Frequency & Monetary:**
   
   In this section, we calculate the recency, frequency, and monetary value for each customer.

- **Calculating RFM Scores:**
   We assign RFM scores to each customer. Each customer is assigned a score for recency, frequency, and monetary value on a scale of 1 to 5, with 5 being the highest score.

- **RFM Customer Segments:**
   
    We segment customers into 9 groups based on their RFM scores:

    **Champions**: Bought recently, buy often and spend the most
    Loyal customers: Buy on a regular basis. Responsive to promotions.

    **Potential loyalis**t: Recent customers with average frequency.

    **Recent customers:** Bought most recently, but not often.

    **Promising:** Recent shoppers, but haven’t spent much.

    **Needs attention:** Above average recency, frequency and monetary values. May not have bought very recently though.

    **About to sleep:** Below average recency and frequency. Will lose them if not reactivated.

    **At risk:** Some time since they’ve purchased. Need to bring them back!

    **Can’t lose them:** Used to purchase frequently but haven’t returned for a long time.

    **Hibernating:** Last purchase was long back and low number of orders. May be lost.

- **Distribution of RFM Values within Customer Segments and Loyal Customer Segments:**
   
   Visualizations help us understand the distribution of RFM values within customer segments, with a special focus on loyal customers.

- **RFM Overall Distribution:**
   
   Visualizing the overall distribution of RFM scores is key to understanding customer behavior.

- **Correlation of the Recency, Frequency, and Monetary Scores within the Engaged Segment:**
   
   We explore the correlation between recency, frequency, and monetary scores within the engaged segment.

- **Recency, Frequency, and Monetary Scores for Each Segment:**
   
   In this section, we provide insights into the recency, frequency, and monetary scores for each customer segment.

## Importing Necessary Libraries

In this section, we import the required Python libraries 

## Loading Data

This section includes code to load the dataset from a CSV file using pandas.

## Data Processing

Here, we perform data preprocessing tasks such as handling missing values, data cleaning, and data transformation.

## EDA (Exploratory Data Analysis)

This section is dedicated to exploring the dataset and creating visualizations to understand its characteristics.

## Product Analysis

For product analysis, this section is divided into sub-sections:

### Total Transaction Amount for Each Product

Calculate and display the total transaction amount for each product with visualizations.

### Number of Orders for Each Product

Calculate and display the number of orders for each product with visualizations.

### Most Common Product Category Purchased in Each Location

Identify the most common product category purchased in each location with visualizations.

### Most Common Product Category with Greatest Revenue in Each Location

Determine the most common product category with the highest revenue in each location with visualizations.

### Distribution of Transaction Amount for Each Product

Visualize the distribution of transaction amounts for each product to gain insights.

## Time Series Analysis

This section contains sub-sections like:

### Patterns or Trends in Count of Orders

Analyze and visualize any patterns or trends in the count of orders over time.

### Transaction Amount for Each Month

Calculate and display the transaction amount for each month using visualizations.

### Revenue per Day for All Months

Calculate and display the revenue per day for all months with visualizations.
## Conclusion


Our analysis began by assigning RFM scores to customers and then classifying them into distinct segments. These segments, including loyal customers, engaged customers, at-risk customers, and new customers, provided a clear view of our customer base's characteristics.and focusing on product & location analysis then Time Series analysis with visualizations.

Thank you for exploring the RFM analysis project.I Will be happy if you connect with me on LinkedIn.

## Contact

- **Mohamed Ibrahim** [![LinkedIn](https://img.icons8.com/color/48/000000/linkedin.png)](https://www.linkedin.com/in/mohamed-ibrahim-513531202/)
