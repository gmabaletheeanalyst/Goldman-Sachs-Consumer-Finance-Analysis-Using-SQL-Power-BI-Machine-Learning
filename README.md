# Goldman-Sachs-Consumer-Finance-Analysis-Using-SQL-Power-BI-Machine-Learning
End-to-end data analytics initiative, integrating advanced SQL querying, interactive dashboards, and machine learning for predictive modeling

<img width="912" height="511" alt="1" src="https://github.com/user-attachments/assets/3e15ab46-6f63-40a6-84bd-38bcfd89052c" />

This dashboard provides a summary of the Goldman Sachs consumer loan portfolio.

**Key Metrics:**

Total Loans Issued: 270,000

Total Loan Amount Disbursed: $4 billion

Average Loan Size: $15,410

Loan Approval Rate: 91.31%

Overall Default Rate: 6.61%

**Insights from Visualizations:**

Total Loan Amount Disbursed vs Total Loans Issued by Issue Year: Both total loan amount and total loans issued have shown a steady increase from 2012 to 2018, indicating consistent growth in the consumer finance portfolio.

Count of Loan Status by Loan Status: The majority of loans are in "Current" status (170,461), followed by "Fully Paid" (76,361). A significant number of loans are "Charged Off" (17,851), which contributes to the overall default rate.

Total Loans Issued by State and Region: The US map shows loan distribution across states. The bar chart indicates that the South and West regions have the highest number of loans issued, while the Midwest has the lowest.

Regional Data Table: The table at the bottom right provides a breakdown of loans issued and amount disbursed by region. The South region has the highest number of loans (97,683) and amount disbursed ($1.51 billion), confirming the insights from the bar chart.

**Summary:** The portfolio is in a healthy growth phase with a high approval rate. While the majority of loans are current or fully paid, the default rate of 6.61% warrants attention and further analysis to understand its drivers. The South and West are the most significant markets for loan issuance.



<img width="912" height="513" alt="2" src="https://github.com/user-attachments/assets/3c7527de-1696-4ca5-ab40-038a851f677d" />

This dashboard focuses on customer centric metrics and risk profiles.

**Key Metrics:**

Total Customers: 270,000

Average Credit Score: 670.76 (which falls in the "Good" range)

Percentage of Fully Paid Loans: 28.25%

% High-Risk Customers: 13.29%

**Insights from Visualizations:**

Percentage of Fully Paid Loans (28.25%): This is a meaningful and healthy metric. It indicates that over a quarter of the loans in the portfolio have been successfully paid off. This suggests a maturing portfolio with a consistent stream of completed loan cycles, which is a positive sign of financial health.

Total Customers by Credit Score Band: The majority of customers have "Good" (650-699) or "Excellent" (700-850) credit scores, indicating a generally high-quality customer base.

Total Customers by Risk Category: 86.71% of customers are classified as "Low-Medium Risk," while 13.29% are "High Risk." This directly corresponds to the key metric.

Total Customers by Employment Length (emp_length): A significant number of customers have long employment histories (89K customers with 10+ years of employment), which is generally a positive indicator of stability.

Total Customers by Home Ownership: Customers who own their homes (MORTGAGE and OWN) make up the majority of the portfolio, which is also a positive indicator of financial stability.

Approval Rate by Segment by Risk Category: This is a crucial insight. The approval rate for "Low-Medium Risk" customers is very high (99%), while the rate for "High Risk" customers is significantly lower (39%). This indicates a well managed credit policy that effectively screens out a large portion of high-risk applicants.

**Summary:** Goldman Sachs maintains a strong customer base with a high average credit score and a prudent lending strategy. The 28.25% of loans that have been fully paid off is a positive indicator of a healthy, maturing portfolio.


<img width="911" height="509" alt="3" src="https://github.com/user-attachments/assets/48c13e80-933d-475d-8ce8-28c8968f1325" />

This dashboard breaks down loan performance by various categories, such as grade and purpose.

**Key Metrics:**

Total Loan Amount Disbursed: $4 billion

Total Customers: 270,000

Default Rate by Category: 6.61%

Avg Interest Rate by Category: 13.08%

**Insights from Visualizations:**

Total Loan Amount Disbursed by Grade: The highest amount of loans are disbursed for "Grade B" and "Grade C," which are typically considered good-to-average credit grades. This aligns with the "Good" average credit score seen in the Customer Risk Analysis.

Total Loans Issued by Term (Donut Chart): A large majority of loans (70.21% or 190,000) are for a 60-month term, confirming the insight from the previous dashboard that these are the most popular.

Total Loan Amount Disbursed by Purpose (Treemap): "Debt consolidation" is by far the largest category for loan amount disbursed, followed by "credit card" and "home_improvement." This is consistent with the financial performance and repayment dashboards.

Default Rate by Category by Purpose (Waterfall Chart): This chart shows the default rate for different loan purposes. "Wedding" and "small business" loans have low default rates, while "credit_card" and "car" loans have higher rates. This provides granular insights into which loan types are performing better or worse.

**Summary:** The portfolio's largest segments are B and C grade loans and 60-month term loans. The analysis reinforces the dominance of debt consolidation loans and highlights which loan purposes carry a higher or lower default risk, which is critical for future underwriting and risk management decisions.

<img width="907" height="511" alt="4" src="https://github.com/user-attachments/assets/240f13db-c54d-42ae-a65c-1fccc4f0d6aa" />

This dashboard focuses on geographical trends and performance metrics.

**Key Metrics (Regional**

Total Loan Amount Disbursed: $4 billion

Overall Default Rate: 6.61%

Regional Approval Rate: 91.31%

Top Risk Region: Northeast

**Insights from Visualizations:**

Total Loans Issued by Region (Treemap): This visualization confirms the dominance of the South region in terms of loans issued, followed by the West, Northeast, and Midwest.

Total Loans Issued by Issue Year: Similar to the first dashboard, this chart shows a clear upward trend in loans issued from 2012 to 2019, reflecting continuous portfolio expansion.

Detailed Table (addr_state): This table provides a state-by-state breakdown of key metrics:

AL (Alabama): Has a relatively high default rate of 8.39% compared to the overall average.

AZ (Arizona): Stands out with a low default rate of 6.51%.

CA (California): The largest state by number of loans (37,024) and amount disbursed ($583 million), with a healthy default rate of 6.82%.

The Northeast is highlighted as the "Top Risk Region," which suggests that despite its smaller loan volume, it might have the highest default rate.

**Summary:** This dashboard provides a deeper dive into regional performance. It confirms the growth and high approval rate seen in the first dashboard while highlighting specific regional and state-level risks and opportunities. The Northeast region is identified as a high-risk area, which could be due to a variety of factors not shown here, such as economic conditions or customer demographics.



<img width="910" height="512" alt="5" src="https://github.com/user-attachments/assets/956d396e-52fd-42b6-9f3f-7b4a530d2f66" />

This dashboard focuses on the repayment behavior of customers and delinquency rates.

**Key Metrics:**

Total Loan Amount Disbursed: $4 billion

Total Loans Issued: 270,000

Percentage of Fully Paid Loans: 28.25%

% Delinquent Loan Percentage: 1.47%

**Insights from Visualizations:**

Percentage of Fully Paid Loans (28.25%): This metric confirms that a healthy portion of the loan book has been fully paid off.

Overall Default Rate and Delinquent Loan Percentage by Issue Year: The default rate and delinquent loan percentage lines show similar trends, which is expected. The high point of both metrics appears to be around 2015-2016.

Total Loans Issued by Purpose and Loan Status: This stacked bar chart provides a detailed breakdown. "Debt consolidation" has the highest number of loans across all statuses, including "Charged Off." This reinforces its high-risk nature, despite being a major source of income.

Delinquent Loan Percentage by Term (Donut Chart): The majority of delinquent loans (59.43%) are from 60-month term loans. This suggests that longer-term loans carry a higher risk of delinquency.

Percentage of Fully Paid Loans by Term (Donut Chart): This chart shows how the 28.25% of fully paid loans are distributed by term. The majority (62.45%) of the fully paid loans are from 60-month term loans. This is a key insight: 60-month loans are both the most popular, contributing the most to delinquency, and also the most common loan term to be fully paid off.

Purpose Delinquent Loan % (Table): This table ranks loan purposes by their delinquency rate. "House" loans have the highest delinquency rate at 2.52%, followed by "major_purchase" and "home_improvement," suggesting these purposes are riskier than others.

**Summary:** While the overall delinquency rate is low at 1.47%, this dashboard reveals significant risk variations by loan purpose and term. The most popular loan term (60 months) contributes the most to both delinquency and successful repayment. The analysis highlights that loans for purposes such as "house" and "major purchase" carry a higher delinquency risk. The 28.25% of fully paid loans is a positive indicator of portfolio maturity.



<img width="911" height="512" alt="6" src="https://github.com/user-attachments/assets/318ddbc8-b742-4fbf-a48e-203c54fc0305" />

This dashboard provides a look at the portfolio's financial health, including interest income and revenue.

**Key Metrics:**

Total Loan Amount Disbursed: $4 billion

Total Loans Issued: 270,000

Interest Income: $5.45 million

% NPL Ratio: 8.29% (NPL = Non-Performing Loans, which is a measure of bad debt)

**Insights from Visualizations:**

Net Loan Revenue and NPL Ratio by Issue Year: This chart shows fluctuations in both metrics over time. The Net Loan Revenue (light blue line) seems to have a similar trend to the number of loans issued. The NPL Ratio (dark blue line) shows some volatility, peaking around 2015-2016 before trending downwards. The 8.29% NPL ratio is a concern and warrants closer attention.

Income from Interest by Purpose (Treemap): The largest source of interest income comes from "debt_consolidation" loans, followed by "credit_card" loans. This suggests that these loan purposes are either the most popular or have higher interest rates.

Income from Interest by Issue Year and Purpose (Stacked Bar Chart): This detailed chart shows how the composition of interest income has changed over time. "Debt consolidation" has consistently been the primary driver of interest income.

**Summary:** The portfolio generates substantial interest income, primarily from debt consolidation and credit card loans. The NPL ratio of 8.29% indicates a considerable level of non-performing assets, which is a significant risk factor that could impact future profitability.









