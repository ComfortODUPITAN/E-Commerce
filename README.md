![GitHub Logo]((https://drive.google.com/file/d/1b2bVL6VzI91Ep8yyUsWFg-5S3BnKeFPq/view?usp=drive_link))

# E-COMMERCE ANALYSIS
An online retail company is concerned about its customer churn rate. To retain customers, the management wants to proactively identify customers who are at a high risk of churning.

Dataset: This dataset was downloaded from Kaggle. A standard version can be found here: [Click here]((https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction))

## RESEARCH QUESTIONS

### Section 1: Customer Overview
•	KPIs: Total Customers, Average Tenure, % Churned, Average Satisfaction
•	Visuals:
o	Pie chart: Customers by Gender
o	Column: Marital Status by Count

### Section 2: Sales & Payment Insights
•	KPIs: Most Used Payment Mode, Avg. Cashback, Avg. Order Amount Increase
•	Visuals:
o	Bar chart: Payment Mode vs CashbackAmount
o	Column: Payment Mode vs CouponUsed

### Section 3: Product & Satisfaction
•	KPIs: Highest-Rated Category, Avg. Satisfaction
•	Visuals:
o	Column chart: PreferedOrderCat vs SatisfactionScore

### Section 4: Retention & Loyalty
•	KPIs: % Churn, Avg. Tenure (Churned vs Retained), % with Complaints
•	Visuals:
o	Line/Bar combo: Satisfaction vs Churn
o	Pie chart: Complaint vs No Complaint

## DATA CLEANING SUMMARY

-	Searched for blanks
-	Found the average to fill the  blanks in columns C (Tenure),G (Preffereed mode of payment),I (Hours spend on app),Q (Order amount),R (Coupon used),S (Order count).

## INSIGHTS AND CONCLUSIONS
1.	Customer Demographics:
o	The customer base consists of 3,383 males (≈60%) and 2,246 females (≈40%), showing a slightly male-dominated audience.
o	Most customers are married, suggesting that the e-commerce platform attracts family-oriented buyers with stable income patterns.
2.	Payment Behavior:
o	Debit cards and credit cards are the most preferred payment modes, with debit cards leading in total transaction volume.
o	E-wallets and UPI are gaining traction, especially among tech-savvy customers, reflecting growing digital adoption.
o	The highest cashback amount is also linked to debit card transactions, showing that cashback incentives may drive payment choice.
3.	Customer Satisfaction & Retention:
o	Satisfaction levels show a clear trend: higher satisfaction correlates with lower churn and higher repeat purchases.
o	Customers who raised complaints represent only 28.49%, but their churn tendency is significantly higher than those who didn’t complain.
o	Churn rate decreases progressively as satisfaction scores rise — proving the importance of after-sales service and customer engagement.
4.	Order and Coupon Trends:
o	The average coupon usage (1.72) indicates moderate engagement with promotional campaigns.
o	A higher number of coupon users tends to correspond with increased cashback rewards and order amount hikes, showing that discounts drive retention and sales growth.
5.	Product Preferences:
o	Laptops & Accessories and Mobile Phones dominate preferred categories, attracting the largest share of high-spending customers.
o	Satisfaction is highest in these tech-related categories, suggesting customers find consistent value and reliability there.

#### How These Findings Answer the Research Questions

1.	What are the main customer characteristics?
Mostly male, married, and urban-based (CityTier 1)

2.	Which payment methods dominate and why?
Debit and credit cards:driven by cashback offers and reliability

3.	How does satisfaction affect churn and loyalty?
Higher satisfaction = lower churn, confirming its direct impact on retention

4.	What product categories are most popular?
Laptop & Accessories and Mobile Phones lead, showing customer tech preference

5.	How do coupons and cashback influence engagement?
Incentives (cashbacks/coupons) directly boost order count and spending growth.

## LIMITATIONS AND FUTURE WORK
### Challenges or Constraints
1.	The dataset lacks temporal (date/time) variables, limiting analysis of seasonal or monthly purchasing patterns.
2.	Geographical details are limited to city tiers : no precise region or country identifiers for market segmentation.
3.	Customer feedback content (e.g., text reviews) is not included, which could add richer insights into satisfaction drivers.
4.	The analysis is static: future integration with Power BI or Python could introduce dynamic trend tracking and forecasting.

### Suggestions for Further Exploration
1.	Add Time Dimension: Incorporate transaction date/time data to study purchase frequency and seasonal spikes.
2.	Customer Segmentation: Use clustering (in Power BI or R) to identify distinct customer personas (e.g., high-value vs. deal-seeking).
3.	Predictive Modeling: Build a churn prediction model using satisfaction, complaint history, and tenure.
4.	Text Analytics: Collect and analyze written feedback to uncover sentiment drivers and pain points.
5.	Profitability Analysis: Introduce columns for revenue, cost, and margin to identify top-performing segments.

## CONCLUSION

The dashboard successfully visualizes customer demographics, behavior, and satisfaction trends. It highlights that payment convenience, cashback rewards, and positive experiences significantly drive retention and loyalty. Strengthening complaint handling and personalizing promotions could further enhance customer satisfaction and reduce churn.


