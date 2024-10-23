# Customer Segmentation: Recency, Frequency, Monetary (RFM) Analysis and K-Means Clustering

## 1. Introduction:

Customer segmentation is a crucial analytical technique that allows businesses to categorize their customer base into distinct groups based on specific behaviors and characteristics. One of the most effective methods for segmentation is through RFM analysis—an approach that evaluates customers based on Recency, Frequency, and Monetary Value. These three metrics provide valuable insights into customer engagement, purchasing behavior, and overall value to the business.

- Recency measures how recently a customer made their last purchase, which helps identify active versus inactive customers.
- Frequency counts the number of transactions a customer has made within a certain period, reflecting their engagement level with the business.
- Monetary Value assesses the total amount spent by a customer during the analysis period, highlighting their financial contribution to the company.

By using RFM analysis, businesses can develop targeted marketing strategies, prioritize high-value customers, and create personalized engagement initiatives to drive loyalty and maximize revenue. This segmentation helps to identify the most valuable customers, re-engage those who are at risk of churning, and optimize resource allocation for customer acquisition and retention.

## 2. Project Details
The project utilizes a dataset of online retail transactions, which includes information on customer demographics, purchase history, and product details. Furthermore, this project is divided into two parts:

1. Exploratory Data Analysis (EDA)
2. Recency, Frequency, and Monetary Value (RFM) Analysis

In EDA, I have explored the data, examined the various features, and identified any missing values or inconsistencies to ensure data integrity and accuracy. Moreover, I have analyzed the characteristics of each segment, and identified their unique purchasing patterns, product preferences, and overall behavior. This analysis provides actionable insights into the motivations and needs of different customers. Also, visualizations are employed since it helps in understanding the key characteristics of each customer segment and their relationship with overall business performance.

In RFM analysis, I have explored how Recency, Frequency, and Monetary Value can be used to group customers into different segments, such as Gold, Silver, and Bronze, as well as Best Customers, lost cheap customers, almost lost customers, and lost customers, allowing for data-driven decision-making that aligns with business objectives. Through this analysis, we aim to uncover actionable insights that can be used to enhance customer relationships and drive business growth.

## 3. Key Insights:

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

![image](https://github.com/user-attachments/assets/464d7354-60dc-44d2-b96c-9ed91bb161ce)

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

**6. Top 11 Countries by Unique Customers:**

![image](https://github.com/user-attachments/assets/2a89ffcf-7adf-4cfc-a570-5a1ab8becb78)

**7. How much sales happened for each product category and how many quantities each category is being sold:**

![image](https://github.com/user-attachments/assets/d91dddeb-ee52-4efe-bade-5a0de9f6f86e)

The image shows two bar charts that rank the top 10 products by unit price and quantity sold. Here's what we can infer from the charts:

**Top 10 Products by Unit Price:**

- Product Diversity: The top 10 products by unit price are quite diverse, ranging from postage items to kitchenware and home decor.
- High-Priced Items: The product with the highest unit price is "POSTAGE," followed by "Manual" and "DOTCOM POSTAGE." This suggests that these items are relatively expensive compared to the other products in the dataset.
- Price Variation: There is a significant variation in unit prices among the top 10 products, with some products being priced much higher than others.

**Top 10 Products by Quantity:**

- Popular Products: The product "WHITE HANGING HEART T-LIGHT HOLDER" appears twice in the top 10, suggesting that it is particularly popular among customers.
- Quantity Variation: There is less variation in quantity sold among the top 10 products compared to unit price, indicating that a smaller number of products account for a significant portion of total sales.

**8. Visualizing Cohort Analysis:**

![image](https://github.com/user-attachments/assets/fc0f1f9d-c94d-4b98-a1fa-69bde73fce17)

The heatmap shows retention trends for different customer cohorts and provides a clear way to identify strong or weak retention periods over time.

Key insights you can infer from the heatmap:

1. Customer Retention Over Time: The retention rate generally decreases as time (cohort index) progresses, which is common as customers tend to drop off after initial engagement. Darker green shades indicate higher retention, while lighter shades suggest a lower retention rate.

2. Best Performing Cohorts: Certain months (e.g., 2010-12, 2011-09) have higher retention rates over time compared to others. These cohorts could represent times when marketing efforts, product offerings, or seasonality led to better customer retention.


**9. Analyzing RFM segments:**

![image](https://github.com/user-attachments/assets/043cac2d-6f37-494a-aff9-8fb5696e9dcd)

- Recency decreases as the RFM score increases**: Customers with higher RFM scores (e.g., 12) have made more recent purchases (lower Recency), while those with lower scores (e.g., 3) haven't made purchases in a while (higher Recency values).

- Frequency increases with RFM score**: Customers with higher scores (e.g., 12) tend to make significantly more purchases than those with lower scores. For example, customers with an RFM score of 3 made an average of 2.1 purchases, while those with a score of 12 made an average of 81.7 purchases.

- Monetary Value generally increases with the RFM score**: Customers with higher scores spend significantly more. Customers with an RFM score of 12 have spent an average of 1,916.2, while those with a score of 3 spent only 21.7 on average.

**High-Value Customers (RFM score 12):**
- These customers make frequent purchases (81.7 on average) and have a low Recency score (they’ve purchased very recently).
- They also generate a significant amount of revenue (1,916.2), making them the most valuable segment.
- This group is highly engaged and should be prioritized for retention and reward programs.

**Engaged Customers (RFM scores 10 and 11):**
- These customers also have a low Recency score (21.3–33.6), meaning they purchase regularly.
- They have high Frequency (25.1–39.8 purchases on average) and spend a lot (427.8–838.8).
- These customers are loyal and valuable, and businesses should continue efforts to keep them engaged.

**At-Risk Customers (RFM scores 6 and 7):**
- These customers have moderate Recency scores (107.7–84.7), meaning it’s been a while since their last purchase.
- They still have moderate to high Frequency (6.4–9.0 purchases on average), indicating they are repeat customers.
- Interestingly, the Monetary Value for score 6 is negative (-62.1), which could be due to returns or discounts, while score 7 customers have a positive value (160.7).
- This segment might be at risk of churn, especially if their recency continues to increase. They could benefit from re-engagement campaigns or incentives.

**Low-Value or Inactive Customers (RFM scores 3 to 5):**
- These customers have high Recency scores (144.3–261.9), indicating they haven't made recent purchases.
- They make very few purchases (2.1–4.5 on average) and spend significantly less (21.7–75.3).
- These customers are either new or inactive and may require targeted marketing to increase engagement, such as special offers or discounts.

**10. Using RFM score to group customers into GOLD, SILVER, and BRONZE segments:**

![image](https://github.com/user-attachments/assets/022d622c-a861-48cf-b22a-26de8bc3bb2b)

**Gold Segment:**
- These are highly engaged, loyal customers who make frequent and recent purchases, contributing significantly to revenue.
- The fact that they have a very low Recency score (27.5) shows that they are actively buying.
- Retention should be a top priority for this group, as losing these customers could have a substantial impact on revenue. Loyalty programs, exclusive offers, and personalized experiences are strategies that could further strengthen their engagement.

**Silver Segment:**
- This group makes occasional purchases and generates moderate revenue. They represent the middle tier of customers and have potential for growth.
- Moderate Recency (100.5) indicates they have not purchased very recently, but they are still active buyers.
- Focus on re-engagement strategies such as targeted promotions or upselling could move them into the Gold tier, enhancing their lifetime value.

**Bronze Segment:**
- These are low-value or inactive customers who haven’t purchased recently and make infrequent purchases. They contribute the least in terms of revenue.
- With a high Recency score (217.3), they are at risk of being lost entirely unless reactivated.
- This group would benefit from reactivation campaigns like win-back offers, discounts, or targeted marketing aimed at re-engaging them.

**11. Customer Segments Distribution (RFM):**

![image](https://github.com/user-attachments/assets/24144513-61a8-49c1-bb2c-065234d2fede)

## 4. K-Means Clustering

After applying Elbow method and Silhouette Score Method, I decided to select K = 4 as the number of clusters because its Silhouette Score was higher than other clusters.

**Relative importance of segment attributes**
- Useful technique to identify relative importance of each segment's attribute
- Calculate average values of each cluster
- Calculate average values of population
- Calculate importance score by dividing them and subtracting 1 (ensures 0 is returned when cluster average equals population average)

This concept helps in understanding how each attribute (e.g., Recency, Frequency, and MonetaryValue) contributes to differentiating customer segments (clusters). By calculating the relative importance of each attribute for each cluster, you can identify which attributes are more significant in defining that specific cluster compared to the overall population.

![image](https://github.com/user-attachments/assets/d47066e1-da6b-40f9-8f91-be260cbc865d)

This heatmap illustrates the relative importance of attributes (Recency, Frequency, and Monetary Value) across different customer clusters generated from K-means clustering. 

1. Cluster 0:
- Recency and Frequency have low positive values (0.03 and 0.17), indicating that customers in this cluster tend to have recent purchases and a moderate frequency of transactions.
- MonetaryValue is essentially 0, indicating that spending per transaction or total spend is very low.

2. Cluster 1:
- Recency has a strong negative value (-1.00), meaning customers in this cluster have made purchases long ago (they are likely lost or inactive).
- Frequency and MonetaryValue are also strongly negative (-0.50 and -0.98), indicating these customers purchase infrequently and have very low spend.

3. Cluster 2:
- Recency is moderately positive (0.29), suggesting recent activity but not the most recent compared to other clusters.
- Frequency is negative (-0.56), showing that these customers don't buy often.
- MonetaryValue is close to zero, suggesting they may spend very little per transaction.

4. Cluster 3:
- Recency is negative (-0.52), indicating that customers haven't purchased recently.
- Frequency has a strong positive value (0.57), indicating that these customers purchase frequently.
- MonetaryValue is essentially 0, meaning they may not be high spenders despite frequent purchases.

## 4. Recommendations

**Based on the above R-F-M score, we can give some Recommendations.**

- Best Customers: We can Reward them for their multiples purchases. They can be early adopters to very new products. Suggest them “Refer a friend”. Also, they can be the most loyal customers that have the habit to order.
- Lost Cheap Customers: Send them personalized emails/messages/notifications to encourage them to order.
- Big Spenders: Notify them about the discounts to keep them spending more and more money on your products
- Loyal Customers: Create loyalty cards in which they can gain points each time of purchasing and these points could transfer into a discount

**Based on GOLD, SILVER, and BRONZE Segments:**
- Gold Segment (41.5 average transactions, $884.3 spend) represents the core of the business’s revenue and should be prioritized for retention and engagement strategies. This segment contributes the most financially and is highly engaged with the brand.
- Silver Segment (8.1 average transactions, $94.3 spend) presents growth potential. Efforts to increase their purchase frequency and spending could potentially upgrade them to the Gold tier. They are a large group, so improving their engagement can have a significant cumulative effect on revenue.
- Bronze Segment (2.6 average transactions, $30.9 spend) represents at-risk or low-engagement customers. These customers require a different strategy, focusing on re-engagement and trying to bring them back into regular purchasing habits.
