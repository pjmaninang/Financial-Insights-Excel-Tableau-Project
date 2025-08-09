# Financial Customer Insights & Risk Metrics - Excel/Tableau Project

## Project Overview

This financial institution was seeking a comprehensive analysis of its customers throughout the 2010s, using a transaction-focused dataset. The provided data encompasses a substantial volume of customer transactions over the decade, supplemented by key customer profile attributes. Through detailed analysis and visualization, this project uncovers actionable insights into customer value, spending behavior, and financial risk, enabling the institution to inform strategic decision-making, optimize customer engagement, and identify opportunities for growth.

Using Excel Power Query to clean the data, and Tableau for visualization, insights and recommendations were focused on these objectives:

- Identify the most valuable customer segments by state, age group, and transaction behavior, using metrics such as total customers, average spending per customer, and total transaction counts
- Compare spending patterns and transaction volumes across different age groups to uncover high-value demographics and potential growth opportunities
- Assess customer financial health using Debt-to-Income (DTI) ratios and credit utilization levels segmented by credit score brackets
- Highlight customers exceeding healthy credit utilization thresholds to pinpoint areas of potential credit risk and inform mitigation strategies

An interactive Tableau dashboard of the dataset can be found and downloaded [here](https://public.tableau.com/app/profile/pj.maninang/viz/SyntheticFinancialTransactions/FinancialInsightsDashboard)

The cleaned excel file used to combine some of the raw data files can be found [here](https://github.com/pjmaninang/Financial-Insights-Excel-Tableau-Project/blob/main/Power%20Query%20Cleaned%20Data.xlsx)

The raw data files can be found [here](https://github.com/pjmaninang/Financial-Insights-Excel-Tableau-Project/blob/main/raw%20data.zip) and the large raw transaction file link [here](https://github.com/pjmaninang/Financial-Insights-Excel-Tableau-Project/blob/main/transaction_raw_data_link)

## Data Structure

The dataset provided by the company contained three separate CSV files - cards_data.csv, users_data.csv, and transactions_data.csv - with the tables structured as so:

![Tables](

## Executive Summary

### Overview of Findings

The institution’s customer base is heavily concentrated in California, Texas, Florida, and New York, which together account for over 25% of total customers and lead the nation in transaction volumes—making them pivotal to overall performance. High-spend demographics, particularly customers aged 45–54 and 65+, are driving the greatest average spend per customer, while lower-income brackets ($11.9K–$48.4K) dominate transaction counts, representing the institution’s core market segment. However, credit risk is elevated in key regions, with New York, Oregon, and Washington showing utilization rates far above the healthy benchmark, and customers in Poor and Fair credit brackets exhibiting significant over-leveraging. These trends underscore both the opportunity to strengthen high-value markets and demographics, and the urgent need for targeted credit risk mitigation in vulnerable segments

Below is a top overview from the Tableau dashboard

![Top Overview](https://github.com/pjmaninang/Financial-Insights-Excel-Tableau-Project/blob/main/Top%20Overview.png?raw=true)

## Findings and Insights

### Customer Distribution & Value Analysis

- California (244), Texas (159), Florida (131), and New York (124) collectively account for over one-quarter of the institution’s U.S. customer base. This concentration highlights a substantial reliance on a few high-population states, making these markets critical to sustaining and expanding overall performance
  - These four states not only lead in customer count but also generate the highest transaction volumes by a significant margin
- Beyond California’s dominance, the majority of customers are concentrated in states spanning from the Central to Eastern U.S., indicating regional market strength in these areas
- Wyoming, Idaho, and both Dakotas represent the smallest market presence, each with six or fewer customers. This extremely limited footprint suggests untapped market potential, where even modest growth initiatives could deliver proportionally large percentage gains in customer acquisition
- Rhode Island ($766K), Colorado ($662K), and Virginia ($630K) achieve the highest average spend per customer nationwide, despite each having fewer than 50 customers — suggesting potential for targeted, high-value customer engagement strategies in these markets

### Spending & Trnasaction Behaviors 

- Customers aged 45–54 and 65+ exhibit the highest average spend per customer at $496K and $500K respectively, suggesting these groups are critical to driving high-value sales despite potentially smaller customer counts
- The 18–24 age group has both the lowest average spend ($193K) and the lowest transaction volume (16K transactions), indicating low engagement and potential missed lifetime value if not nurtured early
- The 45–54 age group leads transaction activity with 3.5M transactions, followed closely by 65+ with 3.1M and 35–44 with 2.8M. This suggests middle-aged and senior customers are the most engaged repeat buyers
- Customers earning $11.9K–$48.4K annually account for over 8.4M transactions—nearly double that of the next highest income bracket—indicating that the institution’s core market lies within lower-to-middle income earners
- The $48.4K–$103.3K bracket generates 4.3M transactions, demonstrating strong purchasing behavior that could be further cultivated with targeted upsell and cross-sell strategies

### Customer Credit Risk Evaluation

- Despite ranking fourth in total customers and transactions, New York stands out with an average credit utilization of 182%—over four times the healthy benchmark and far exceeding the ~40% average observed in the other top three states. This suggests that a significant portion of New York’s customer base may be operating under high credit strain despite their large transaction volume
- Oregon (323%) and Washington (227%) record some of the highest average credit utilization rates in the nation, indicating a potential regional pattern of elevated credit dependence that warrants closer examination for risk mitigation strategies
- Customers in the Poor (93%) and Fair (111%) credit score brackets have utilization rates more than 3x the recommended healthy threshold of 30%, indicating significant over-leveraging and heightened default risk
- Exceptional credit customers maintain an average utilization of just 28%, well below the healthy threshold, reflecting disciplined credit management and reduced risk exposure
- The concentration of extreme DTI ratios and high utilization in the Poor and Fair segments highlights an opportunity to implement proactive intervention strategies—such as credit counseling, debt restructuring, or product adjustments—to mitigate potential losses


## Recommendations

- Deepen engagement in California, Texas, Florida, and New York through targeted loyalty programs, premium product offerings, and localized marketing, capitalizing on their combined share of over 25% of the customer base and leading transaction volumes
- Prioritize retention and upselling efforts for the 45–54 and 65+ age groups, which deliver the highest spend and strong transaction volumes, while developing targeted engagement strategies for the 18–24 segment to unlock future lifetime value
- Implement proactive credit risk management in New York, Oregon, and Washington, including credit monitoring, debt restructuring offers, and educational programs, while leveraging insights from Exceptional credit customers to model best practices across the portfolio
- Launch acquisition campaigns in underserved states such as Wyoming, Idaho, and the Dakotas, where even modest growth could result in significant percentage gains in customer base size and brand footprint

## Limitations

- Total debt is not broken down into yearly or monthly payments per customer, so the DTI figures are more of a broad DTI figure based on overall total debt and yearly income
