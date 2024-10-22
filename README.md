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

**2. InvoiceDate (Time-Based Trends):**
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
   
**3. UnitPrice (Pricing Analysis):**
How does the price distribution look? Are there outliers in the pricing structure?
![image](https://github.com/user-attachments/assets/c45a77cb-ea32-4d4d-adaf-ad6bb99f1b47)

The histogram shows the distribution of unit prices in a dataset. Here's what we can infer from it:

**Distribution:**

- The distribution is highly skewed to the right, meaning there are a few very high unit prices that pull the mean to the right.
- The majority of unit prices are between 0 and 2, with a peak frequency around 1.
- There is a long tail to the right, indicating the presence of some high-priced items.

**Insights:**

- The majority of products are priced relatively low, with a few high-priced items that skew the distribution.
- This distribution suggests that there might be a few premium products or luxury items that are driving the overall average unit price.
- The long tail to the right indicates that there is a significant range of prices, suggesting that the dataset includes products from various categories or brands.

Overall, the histogram provides a visual representation of the unit price distribution, highlighting the skewness and the presence of high-priced items. This information can be valuable for understanding the pricing structure of the dataset and making informed decisions about product pricing and marketing strategies.

**4. CustomerID (Customer Behavior):**
How many unique customers are there? Are there repeat customers, or do most customers make a single purchase?

![image](https://github.com/user-attachments/assets/75833935-18de-4133-a652-d98affcaa6e2)

- Customers are classified as either 'new' or 'repeat' based on their purchase count.
- A pie chart is used to show the percentage split between new and repeat customers.

**5. Country (Geographical Analysis):**
Map Plot: Geographical Heatmap Showing Concentration of Customers by Country

![image](https://github.com/user-attachments/assets/bf6568b0-3671-4e59-a94f-c3a93c87d090)

The geographical heatmap shows the number of unique customers by country. Here are some insights that can be inferred from it:

**Customer Concentration:**

- The map highlights regions with higher concentrations of unique customers. In this case, it appears that there are more unique customers particularly in the United Kingdom and surrounding countries.
- Other regions, such as North America, Australia, and parts of Asia, also have a significant number of unique customers, but the concentration is lower compared to UK.

**Geographic Distribution:**

- The map provides a visual representation of the geographic distribution of customers. This can be helpful in understanding the market reach and identifying potential growth opportunities.
- For example, if a business is primarily focused on the European market, the map suggests that there might be opportunities to expand into other regions with a growing customer base.
