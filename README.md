# Zomato-Data-Analysis

This project demonstrates a step-by-step process for analyzing Zomato data using AWS services and Python.

Steps Involved
# 1. Data Storage in S3 Bucket
Uploaded the raw Zomato dataset to an S3 bucket for secure and scalable storage.
# 2. Data Cleaning in Jupyter Notebook
Performed an initial analysis of the dataset.
Identified missing, duplicate, and irrelevant data.
# 3. Data Transformation in AWS Glue

![Screenshot (24)](https://github.com/user-attachments/assets/68e76046-deff-48a1-ab74-96cf585bff26)
Transferred the dataset to AWS Glue for advanced cleaning and transformation.
Applied transformations such as dropping unnecessary columns, handling missing values, renaming columns, and standardizing formats.
# 4. Code Execution in AWS Glue
Pasted the transformation code into AWS Glue.
Cleaned and processed the data using PySpark within Glue.
# 5. Export of Cleaned Data to S3

![Screenshot (25)](https://github.com/user-attachments/assets/972be76f-c3af-44b7-8aed-b999b1ebc631)

Saved the transformed and cleaned dataset back into an S3 bucket.
# 6. Data Visualization with Amazon QuickSight
Connected the cleaned dataset in S3 to Amazon QuickSight.
Created insightful visualizations and dashboards to analyze Zomato's trends, customer preferences, and restaurant performance.
