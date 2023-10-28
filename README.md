# WALMART Confidence-Interval-and-Central-Limit-Theorem

## About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores in the United States. Walmart has more than 100 million customers worldwide.


## Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).


## Dataset

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:

User_ID:	User ID

Product_ID:	Product ID

Gender:	Sex of User

Age:	Age in bins

Occupation:	Occupation(Masked)

City_Category:	Category of the City (A,B,C)

StayInCurrentCityYears:	Number of years stay in the current city

Marital_Status:	Marital Status

ProductCategory:	Product Category (Masked)

Purchase:	Purchase Amount


## Insights:
1. By using the Central Limit Theorem (CLT) with bootstrapped samples, we can see that the sample mean of bootstrapped is close to the population mean for all the features with respect to purchase.
2. There is no overlapping in purchasing expenditure between male and female customers.
3. There is no statistically significant difference in purchasing power between married and single people.
4. User ID 1001680 is the most frequent customer, followed by 1004277 and 1001941, respectively.
5. The majority of customers only stay in the city for one year, making up 35% of the customers.

## Recommendations:
1. Walmart can increase purchases by running campaigns for Women's Day, and Mother's Day.
2. Walmart can launch special schemes for women like discounts, coupons, etc.
3. Walmart can advertise with banners and fliers in city categories where sale is comparatively low (like city category A, and C)
4. Walmart can identify repetitive customers (who place more number of orders) and retain them with some discount on future orders
5. Walmart can advertise more for product category who's sales is low

