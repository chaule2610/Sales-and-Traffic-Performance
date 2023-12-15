# Sales-and-Traffic-Performance
Using Excel, and PowerBI to process and visualize different  metrics about the sales and traffic performance of Seller A in  July 2019 to provide key insights that can be valuable in  proposing solutions for Seller A to double revenue in August.

## I. Description
### 1. What: 
- Objective: The primary objective is to achieve a gross revenue of 20 billion VND for seller A in August doubling the achievement of 10 billion VND in July.
- Dataset: historical sales performance (internal Order Management System) and traffic source performance (Google Analytics).
### 2. Who
- This project is presented to seller A.
### 3. Why
- Understand the historical sales performance and traffic source performance to find key insights.
- Provide actions and recommendations to help Seller A achieve their KPI.
### 4. How
- Excel - Data Preprocessing.
- PowerBI - Data Preprocessing and Visualization.
  
## II. Data Preprocessing
### With Excel
- Using the Filter to check values in each column.
- Checking the data type of each column.
- Using conditional formatting to check the duplicated data.
- Remove unnecessary values (both the 'voucher platform' and 'voucher seller' columns have a value of 0 -> remove columns).
### With PowerBI
- For the customer traffic table, split the 'source/medium' column into two columns using the 'Split Column' function.
- Using DAX to create some calculated columns and measure.

## Data Visualization
### Seller A's sales performance in July 2019
![image](https://github.com/chaule2610/Sales-and-Traffic-Performance/assets/120628995/5695b7ec-deb6-4cab-a1c7-fea886783530)

### Seller A's traffic performance in July 2019
![image](https://github.com/chaule2610/Sales-and-Traffic-Performance/assets/120628995/5690da07-6605-4a85-bf11-2d9e93d9d982)

## Key Insights
### Finding from Customer Order
- The gross revenue and the number of products sold gradually increased from the 7th day and peaked on the 12th day of July, after which it significantly declined until the end of the month.
- The top 5 payment methods with the highest gross revenue are Cash on Delivery, Airpay GIRO, Cybersource, Airpay Wallet V2, and VN Air Pay Ibanking (Vietcombank).
- The high sale prices are typically paid for using electronic payment.
- The gross revenue of orders with the 'complete' order status is greater than that of orders with the 'cancel' order status (four times higher).
- The shipping fee also affects the order status, as it can be seen that with a higher average shipping fee, buyers tend to be more inclined to cancel their orders.
### Finding from Customer Traffic
- The top 5 sources with the highest number of users are Google, YouTube, direct, Facebook, and Youtube.com.
- The number of new users is nearly equal to the number of existing users.
- The majority of new users are primarily in the mediums: cpc, social, (none), and referral.
- The number of new users from cpc is the highest.
- Google CPC bring the most revenue.

## Suggestion
### Based on Findings from Customer Order
- Increase the Number of Products Sold.
- Optimize Payment Methods: Encourage using electronic payment methods by offering incentives, promotions, and integrating convenient payment options.
- Promotional Campaigns: Implement various promotional campaigns and discounts.
- Free Shipping: Implement a free shipping policy for high-value orders or orders that meet a minimum threshold.

### Based on Findings from Customer Traffic
- Focus on High-Performing Sources.
- Maximize CPC and Social: Most new users come from CPC and social media, so allocate more resources to these mediums.  Invest in targeted ad campaigns and content to capitalize on performance.










