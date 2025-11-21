# Bank_Financial_Loan_Python

## Background & Overview
This project focuses on analyzing bank loan data to understand borrower behavior, identify good and bad loans, and generate key performance indicators (KPIs) for loan portfolio assessment. Using Python and its data analysis libraries, this project provides insights into loan applications, funded amounts, repayment patterns, and borrower risk profiles.

The analysis helps in identifying trends in loan repayment, understanding factors contributing to defaults, and providing recommendations to improve lending decisions.

## Data Structure Overview

→ Dataset Size: 38,570 rows and 24 columns

→ Key Columns Include:

→ ID – Unique identifier for each borrower

→ Employment Length

→ Employment Title

→ Ownership Issue Date

→ Loan Status 

→ Address 

→ Member ID 

→ Purpose 

→ Verification Status 

→ Annual Income

→ Loan Amount

→ Loan Payment 

And additional supporting columns relevant for loan and borrower analysis


### Loan Status Grouping:

→ Good Loans: Fully Paid, Current

→ Bad Loans: Charges Off, Defaulted


## Executive Summary

The project performs a comprehensive analysis of bank loans by calculating KPIs for good and bad loans separately. The KPIs include:

→ Total loan applications

→ Total funded amount

→ Total amount received

→ Average interest rate

→ Average debt-to-income ratio


The analysis provides a clear overview of the loan portfolio, highlights patterns in borrower repayment, and identifies key metrics for evaluating loan quality.

 ## Insights & Deep Dive

→ Key observations and deep-dive analysis points from the dataset:

→ Loan Distribution: Majority of loans are categorized as fully paid, indicating a generally low default rate.

→ Interest Rates: High-interest loans tend to correlate with longer repayment periods or higher default probability.

→ Debt-to-Income (DTI) Ratio: Borrowers with higher DTI ratios are more likely to default, making DTI a critical risk indicator.

→ Employment Factors: Longer employment tenure and stable job titles correlate with a higher likelihood of fully paid loans.

→ Loan Purpose: Certain loan purposes (e.g., debt consolidation) show patterns in repayment behavior and risk.

→ Verification Status: Verified income borrowers show higher repayment reliability compared to non-verified borrowers.

## Good Loan vs Bad Loan Analysis

→ Good Loans (Fully Paid, Current):

→ Healthy repayment patterns

→ Lower risk indicators

→ Bad Loans (Charges Off, Defaulted):

→ Highlight risk factors: higher interest rates, higher DTI, shorter employment tenure

→ KPIs calculated separately for both categories for performance comparison.

## Recommendations

→ Target borrowers with stable employment, verified income, and lower DTI.

→ Evaluate risk profiles by loan purpose to adjust lending criteria.

→ Optimize interest rates for higher-risk borrowers based on historical data.

→ Perform continuous monitoring of loan KPIs for early warning signs.

→ Implement Python-based dashboards for real-time loan portfolio analysis.


## Tools & Technologies Used

→ Python

→ Pandas, Numpy

→ Matplotlib, Seaborn

→ Jupyter Notebook
