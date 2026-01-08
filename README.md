# Customers RFM Analysis
### Introduction
Recency, frequency, and monetary (RFM) analysis is a customer segmentation technique used to analyze customer behavior based on their most recent purchase, how often they buy, and how much they spend. Examining these three dimensions can help you predict future customer behavior and tailor your marketing efforts to specific customer groups. 
- Recency measures the time since a customer’s last purchase, signaling their current engagement level.
- Frequency tracks how often a customer makes purchases, helping you identify your most consistent buyers.
- Monetary value measures how much customers spend per order, helping you pinpoint high-value customers.

## Objective of the Analysis
The objective of this analysis is to help the company understands the behavioral pattern of the customers by answering the following business questions so as to make informed decision about marketing campaign strategy to reduce churn rate.

## Tools
- Microsoft Excel

## Business Questions
The analysis focuses on answering the following business questions:

1.  Who are our best customers?

2. Which customers require retention campaigns?

3. Which customer segments are safe to deprioritize or ignore?

## Dataset Overview
The dataset contains customer transaction records, including:
Customer ID
Transaction date
Purchase frequency
Total monetary value
From these fields, RFM metrics were calculated to evaluate customer behavior.

## Methodology
The analysis followed these steps:

1. Data Cleaning & Preparation:
   
- Removed duplicates and invalid records

- Ensured consistent date and currency formats

- Aggregated transaction data at the customer level

2. RFM Metric Calculation:
   
- Recency (R): Days since last purchase

- Frequency (F): Number of transactions per customer

- Monetary (M): Total revenue generated per customer

3. Scoring & Segmentation:
   
Customers were scored on each RFM metric using percentile-based ranking

RFM scores were combined to form customer segments such as:

- Best Customers

- Loyal Customers

- At-Risk Customers

- Potential Customers

4. Analysis & Visualization:
   
- Pivot tables and charts were used to compare segments

- Conditional formatting highlighted high- and low-value customers

- Segment-level summaries supported business interpretation

## Key Results & Insights

1. Best Customers

- High Recency, Frequency, and Monetary scores

- Consistently purchase and generate the highest revenue

- Ideal targets for loyalty programs, upselling, and exclusive offers

2.  Customers Needing Retention Campaigns

- Previously high spenders with declining recency

- Risk of churn if not re-engaged

Recommended actions: personalized discounts, reactivation emails, win-back campaigns

3.  Segments Safe to Ignore

- Low frequency and low monetary value customers

- Minimal impact on revenue

- Marketing spend on these segments yields low ROI

## Skills Demonstrated

- Business-focused data analysis

- RFM segmentation methodology

- Microsoft Excel (Pivot Tables, Formulas, Charts, Conditional Formatting)

- Customer analytics & marketing insight generation

- Translating data into actionable business recommendations

## Business Recommendations

- Prioritize retention strategies for at-risk high-value customers

- Invest in loyalty initiatives for best-performing segments

- Reduce marketing spend on low-impact customer groups


## Next Steps

- Automate segmentation using SQL or Python

- Integrate analysis into Power BI for real-time monitoring

- Test campaign effectiveness through A/B experiments

- Incorporate customer lifetime value (CLV) modeling
