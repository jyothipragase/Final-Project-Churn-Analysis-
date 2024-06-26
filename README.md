# CUSTOMER CHURN PROJECT

**Problem Statement**
The problem at hand is to analyze customer churn for a telecommunications company. The company is experiencing a high rate of customer churn, resulting in significant revenue loss. The management wants to identify the key factors contributing to customer churn and develop strategies to reduce churn rate and increase customer retention. The dataset provided includes information about customers, such as demographics, service usage, contract details, and customer churn status.

**AIM:** The challenge is to analyze this dataset using data analytics techniques and uncover insights that can help the company understand the drivers of churn and take proactive measures to retain customers.

**Data Preparation**
 I imported the data into Power BI and transformed it on Power Query as follows:
- Next, I eliminated the auto-generated header, by promoting the first row of my data to become the header.
- Using the given datasets, I have cleaned and removed the Null values and Blank values.
- With the project objective in mind, I sought to eliminate any data that would be irrelevant to my analysis.

**Data Transformation**
 Here, I created Queries to organise data for better analysis and reporting.

-So I created a various calculated measures to create a required fields to create a insights and the required visualization, so I renamed the columns where needed, so they are meaningful enough when they appear as title in the charts.

**Visualization — Report**
I started the report by creating a few DAX measures.
DAX simply means Data Analysis Expression. It is an expression that helps with calculations while building report. I created various measures for the requirement of the visualization:
- Customers(Number of customers)
- Churn rate (%)
- Customers Churned and etc,.

Finally, I built the report in the screenshot below, taking into account the key factors like average income, avg monthly charges, age group, activity status, gender, credit score, e.t.c. and their effects on the churn rate. This helped me gain insights about the process
![Screenshot 2024-06-01 123131](https://github.com/jyothipragase/Final-Project-Churn-Analysis-/assets/164172544/0b0f789c-a8c8-4e16-bea7-26df26702f1c)
![Screenshot 2024-06-01 123157](https://github.com/jyothipragase/Final-Project-Churn-Analysis-/assets/164172544/787881fb-dda4-4f9a-ba8b-c5065debd0aa)

**Conclusion**
In this Power BI analysis, I went through some major data analysis process to get the data from raw to cleaned and onto building the report, ensuring data quality across board. Most importantly, it provided valuable insights into some of the major factors that encourage customer churn at the Telecommunication company.
With this report, we can better manage the churn situation, by focusing on the key factors and evaluating the results of their changes periodically.

**Business Insights and Recommendations**
-The business can use this model to identify customers who may churn.
-Business may provide introductory offers to attract new customers and exclusive offers to existing new customers.
-Marketing team can target Single/M customers with special discounts on paid channels and/or movies to customers.
-Provide targeted offers to Female customers from the Regular account segments.
-Also provide exclusive family offers for Married customers as churn rate is higher among them.
