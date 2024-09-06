# Customer Segmentation and Behavior Analysis
The dataset I worked with consists of transactional data from a chain of grocery stores named Mondrian, covering the period from the start of 1997 to the end of 1998. The data contains records of 32,591 customer transactions and includes several key tables such as Sales Data, Customer Information, Product Information, Time Information, and Store Information.

Key variables in the dataset are:

Customer ID: Used to identify each customer uniquely and link demographic and geographic information.
Product ID: Identifies the products purchased.
Store Sales and Store Cost: Capture the sales revenue and costs incurred from each transaction.
Unit Sales: Represents the number of units purchased in each transaction.
Analysis Overview
CLV (Customer Lifetime Value) Calculation: I computed Customer Lifetime Value (CLV), which is the projected revenue a customer will generate throughout their relationship with the business. Using financial data from customer transactions, I applied the CLV formula and discounted cash flows over time to estimate long-term value. This helps identify valuable customers who contribute significantly to the company's revenue.

RFM Analysis: You performed Recency, Frequency, and Monetary (RFM) analysis. This is a powerful method for segmenting customers based on their transaction history:

Recency (R): How recently a customer made a purchase.
Frequency (F): How often they made purchases.
Monetary (M): The total value of their purchases.
Based on this, I segmented the customers into different groups (such as high-value or lapsed customers) by assigning scores (High/Low) and created different customer profiles based on these attributes.

Customer Segmentation: Using the results of the RFM analysis, I categorized customers into distinct segments. For instance, high-value segments (customers with high recency, frequency, and monetary scores) versus less engaged segments. This segmentation enables targeted marketing strategies aimed at retaining high-value customers or re-engaging inactive ones.

Association Rule Mining: Finally, I applied association rule mining using the Apriori algorithm. This technique identifies patterns in customer buying behavior, such as frequent itemsets that are often purchased together.
