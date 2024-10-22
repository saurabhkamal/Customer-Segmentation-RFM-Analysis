# Customer Segmentation Recency, Frequency, Monetary (RFM) Analysis

## Introduction:

Customer segmentation is a crucial analytical technique that allows businesses to categorize their customer base into distinct groups based on specific behaviors and characteristics. One of the most effective methods for segmentation is through RFM analysis—an approach that evaluates customers based on Recency, Frequency, and Monetary Value. These three metrics provide valuable insights into customer engagement, purchasing behavior, and overall value to the business.

- Recency measures how recently a customer made their last purchase, which helps identify active versus inactive customers.
- Frequency counts the number of transactions a customer has made within a certain period, reflecting their engagement level with the business.
- Monetary Value assesses the total amount spent by a customer during the analysis period, highlighting their financial contribution to the company.

By using RFM analysis, businesses can develop targeted marketing strategies, prioritize high-value customers, and create personalized engagement initiatives to drive loyalty and maximize revenue. This segmentation helps to identify the most valuable customers, re-engage those who are at risk of churning, and optimize resource allocation for customer acquisition and retention.

## Project Details
The project utilizes a dataset of online retail transactions, which includes information on customer demographics, purchase history, and product details. Furthermore, this project is divided into two parts:

1. Exploratory Data Analysis (EDA)
2. Recency, Frequency, and Monetary Value (RFM) Analysis

In EDA, I have explored the data, examined the various features, and identified any missing values or inconsistencies to ensure data integrity and accuracy. Moreover, I have analyzed the characteristics of each segment, and identified their unique purchasing patterns, product preferences, and overall behavior. This analysis provides actionable insights into the motivations and needs of different customers. Also, visualizations are employed since it helps in understanding the key characteristics of each customer segment and their relationship with overall business performance.

In RFM analysis, I have explored how Recency, Frequency, and Monetary Value can be used to group customers into different segments, such as Gold, Silver, and Bronze, as well as Best Customers, lost cheap customers, almost lost customers, and lost customers, allowing for data-driven decision-making that aligns with business objectives. Through this analysis, we aim to uncover actionable insights that can be used to enhance customer relationships and drive business growth.

## Key Insights:

**1. InvoiceNo (Transaction Analysis):**
How many transactions (invoices) are generated over time? Are there seasonal trends in transaction volume?
![image](https://github.com/user-attachments/assets/02bf1ae6-68bb-4547-a74e-3a82adff225a)

![image](https://github.com/user-attachments/assets/6ac02418-590e-4c8e-b3dd-f4c6ec051b41)

The bar chart shows the monthly distribution of transactions (invoices) over a period from January 2010 to December 2011.

Here's what we can learn from the chart:

- Overall trend: The number of invoices generally increases in 2011, with a significant spike in May 2011.
- Peak period: The highest number of invoices occurred in May 2011.
- Seasonal patterns: There seems to be a slight seasonal variation, with higher numbers of invoices in the later part of the years (2010 and 2011, but higher in 2011).
- Low periods:** The lowest number of invoices occurred in the months of 2010.

Overall, the chart provides a visual representation of the transactional activity over the given period, highlighting the peak periods and any seasonal patterns.

**2. InvoiceNo (Transaction Analysis):**
Showing purchase activity by day of the week and hour to see peak shopping times
![image](https://github.com/user-attachments/assets/adb782a2-b88c-45e9-a419-80253c2c4ea0)

The heatmap provides a visual representation of purchase activity by day of the week and hour of the day. The color intensity indicates the number of purchases made during that specific time period.

Here are some key insights from the heatmap:

- Peak activity: The highest number of purchases occurs on Thursday at 17:00 (5:00 PM), with a total of 45,916 purchases.
- Weekday patterns: Weekdays generally have higher purchase activity than weekends, with Thursday and Friday being the busiest days.
- Hourly patterns: The busiest hours are typically in the afternoon and evening, with a peak around 17:00 (5:00 PM).
- Weekend trends: Weekends have lower overall purchase activity.
- Quiet periods: The early morning hours and late evening hours tend to have lower purchase activity.

Overall, the heatmap provides a clear visualization of the busiest days and times for purchases, which can be valuable for businesses in optimizing their operations and marketing strategies.
   
