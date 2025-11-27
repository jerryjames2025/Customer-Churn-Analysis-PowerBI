INSIGHTS

Most churned customers are on Month-to-Month plans.

Customers with higher monthly charges tend to churn more.

Younger customers (18–29) churn the most.

Customers who stayed less than 1 year have the highest churn rate.

Longer-tenure customers are more loyal.

CUSTOMER CHURN ANALYSIS

This Power BI dashboard shows why customers leave a company.  
It uses a simple dataset with Age, Tenure, Charges, Contract Type, and Churn.

WHAT I BUILT

- Total Customers
- Total Churned Customers
- Churn Rate
- Churn by Contract Type
- Churn by Age Group
- Churn by Tenure Group
- Relation between Monthly Charges and Churn

SIMPLE MEASURES

Total Customers = COUNTROWS('customer_churn')

Churned Customers =
COUNTROWS(FILTER('customer_churn', 'customer_churn'[Churn] = "Yes"))

Churn Rate = [Churned Customers] / [Total Customers]

TOOLS USED

- Power BI
- Basic DAX
