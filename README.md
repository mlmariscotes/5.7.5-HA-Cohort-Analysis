## HA 5.7.5 Cohort Analysis
Data Summary
We are given an online retail dataset containing transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.

We are tasked to determine cohorts based on user retention and to provide insights and recommendations to improve customer loyalty.

Our data contains the following columns:

1. **InvoiceNo:** Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'C', it indicates a cancellation.
2. **StockCode:** Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
3. **Description:** Product (item) name. Nominal.
4. **Quantity:** The quantities of each product (item) per transaction. Numeric.
5. **InvoiceDate:** Invoice date and time. Numeric. The day and time when a transaction was generated.
6. **UnitPrice:** Unit price. Numeric. Product price per unit in sterling (Â£).
7. **CustomerID:** Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
8. **Country:** Country name. Nominal. The name of the country where a customer resides.

### Result
![image](https://github.com/mlmariscotes/M5.7.5-Cohort-Analysis-Homework-Assignment/assets/99033220/d8486f38-836f-4549-a622-7ed0e731f76e)

**Insights**

1. 93% of the customers made a single transaction on December 2009
2. First transaction of each month keep declining till December of 2010
3. December 2009, customer only maid 15 transaction
4. Highest pick of transaction is on November 2010
   
**Recommendations**

1. Due to low retention rate in the begining of the month, we may stratigize a marketing plan to increase customer interaction.
2. Have bigger inventory and sales strategy on in-demand products.
3. Offer loyalty points or discount on every first week of the month
