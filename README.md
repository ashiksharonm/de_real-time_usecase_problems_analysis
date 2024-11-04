# de_real-time_usecase_problems_analysis

This project demonstrates the real-time use cases for data engineering.

Done by: Ashik Sharon M
Register No: 24MAI0098
Programme: M.Tech AI ML
Course: Data Engineering


Use Case 1: Real-Time Sales Data Analysis and Insights           

Problem Statement:
                                  You are working for a retail company that wants to gain insights into their sales performance across different stores and products. The company has been collecting real-time sales data from multiple stores, and your task is to clean, process, and analyze the data to derive meaningful insights and create visual representations.

Sample Data Structure:
Sales Data File (sales_data.csv)
Date: (e.g., "2024-11-01", "2024-11-02")
Store ID: (e.g., "S001", "S002")
Product ID: (e.g., "P001", "P002")
Units Sold: (e.g., 50, 75)
Sales Amount: (e.g., 500.75, 1200.50)
Discount Applied: (e.g., 10.5, 5.0)
Customer Segment: (e.g., "Regular", "Premium", "New")

Tasks for Students:

1.    Data Cleaning: Handle missing values, incorrect formats, and outliers.

2.    Data Aggregation: Aggregate sales data at different levels, such as by date, store, and product.

3.    Analysis: 
                     o   Calculate total sales and average sales per product.
                     o   Identify the store with the highest sales performance.
                     o   Analyze the impact of discounts on sales amounts.

4.    Visualization:
                   Use tools like Pandas and Matplotlib to visualize:
                     o   Sales trends over time.
                     o   Sales distribution across different stores.
                     o   Performance comparison of products.

Expected Outcome:
                Students should present a cleaned and well-structured dataset along with meaningful visualizations and insights that can help the company make data-driven decisions.


 --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Use Case 2: Data Pipeline for Customer Feedback Analysis         


Problem Statement:
                        A tech company collects customer feedback data from different channels such as emails, social media, and surveys. The feedback contains structured (ratings) and unstructured (comments) data. Your job is to build a data pipeline to ingest, clean, and analyze this feedback to identify key trends and sentiment.

Sample Data Structure:
Feedback Data File (feedback_data.csv)
Customer ID: (e.g., "C12345", "C67890")
Feedback Channel: (e.g., "Email", "Social Media", "Survey")
Rating (1-5): (e.g., 3, 4, 5)
Comment:
(e.g., "The service was great!", "Could improve product quality.")
Date:
(e.g., "2024-11-01", "2024-11-02")


Tasks for Students:

1.    Data Ingestion: Use tools like Apache Kafka or Apache Spark to ingest data in real time.

2.    Data Cleaning: Process and clean the comments by removing unnecessary characters, correcting misspellings, and handling missing values.

3.    Sentiment Analysis: Perform sentiment analysis on the unstructured text data to classify feedback as positive, neutral, or negative.

4.    Trend Analysis: 
                        o   Analyze feedback trends over time.
                        o   Determine which feedback channels generate the most negative or positive comments.
                        o   Calculate average ratings per channel and identify areas for improvement.

5.    Data Visualization: Create visualizations to show sentiment distribution, feedback trends, and channel performance.


 Expected Outcome:
                                Students should create an end-to-end data pipeline that processes feedback data and provides  insights through sentiment analysis and trend visualizations. The final output should be a report with actionable insights for improving customer satisfaction.
