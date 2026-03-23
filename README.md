## Credit Card Dashboard

## 1.Credit Card Analytics: Customer Risk and Financial Behavior Dashboard
A dynamic, interactive data visualization tool built to analyze credit card customer data—focusing on spending behavior, financial stability, risk segmentation, credit utilization, and customer-level insights for smarter decision-making.

## 2.Project Purpose
The Credit Card Analytics Dashboard is an interactive Power BI report designed to analyze customer financial behavior, credit usage, and risk patterns through a clear and structured visual experience. It exists to help analysts and decision-makers identify high-risk customers, understand spending and repayment trends, analyse the factor affecting revenue and support smarter credit-related business decisions.

## Objectives
- To visualize key customer metrics such as demographics, income, and card usage.
- To identify and balance the risk behavior of customer.
- To analyze transaction trends by expenditure type, week, and card category.
- To enable interactive exploration through filters and slicers for:
1. Gender (Male / Female)
2. Age Group (18–25, 26–35, 36–45, 46–55, 56+)
3. Income Group (Low, Medium, High)
4. Card Category
5. Transaction Week
6. Expense Type

## Significant Measures
**Financial Stability Score-** The Financial Stability Score is a metric used to evaluate the overall financial health of the each customer.Company can use this metrics to make smarter decisions in credit approval, customer targeting, and risk management. 

**DAX**: Financial_Stability_Score = Financial_Stability[Income_score] + Financial_Stability[Asset Score] + Financial_Stability[Behaviour Score]. 

**Financial Risk Score-** The Financial Risk Score represents the likelihood of a customer facing financial difficulty in managing their credit obligations.It can be used to classify customers into different risk categories, enabling businesses to assess creditworthiness, reduce default risk and balance the risk and profit.

**DAX**: Risk_Score = Financial_Risk[Utilization_score] + Financial_Risk[Debt_Score] + Financial_Risk[Income_Score] + Financial_Risk[Payment_behaviour]

**Per Dependent Income-** Per Dependent Income represents the amount of income available for each dependent in a customer’s household. It shows how income is distributed across dependents and helps understand the customer’s financial burden.
DAX: Per_dependent_income = Round(customer[Income]/(customer[Dependent_Count]+1),0).

## Insights
**Sales & Profit**
-	Customer total spendings are higher around mid of every month
-	A strong positive correlation (approx. 0.8) exist between customer total spendings and company profitability.
-	Company generated $11.2 M profit this year, with 72% directly came from customer interest.

**Customers**
-	Majority of customers (around 80%) fall between the 36–55 age range, with female customers representing 58% of the total.
-	Only 57% of user have activated their credit card, Notably, Half belongs to Middle Class Segment (income 50k-100k).
-	High risky customer has major stake in total customer.		

**Risk Analysis**
-	The medium - income segment (50k-100k)  have maximum credit utilization around 40%.
-	Risk factor is highly dependable on financial stability, with high stable consumes more.

**Spendings & Transaction**
-	Customer spent $11.2M of their total spendings toward bills payment.
-	70% People prefer or select swipe option to make payments.

## Tools & Technologies
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel (for initial data formatting)
- Data Modeling & Relationships
- Interactive Filters & Slicers

## Conclusion
The Credit Card Dashboard provides a clear overview of customer spending patterns, revenue contribution, and credit usage behavior. It helps identify key trends such as payment preferences, spending distribution, and the relationship between credit limits and customer activity.

