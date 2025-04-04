# Banking Transactions Analysis Report

## Problem Statement
**Titanic City Bank**, a financial institution, seeks to improve its customer transaction monitoring and account activity tracking. The bank wants to identify trends in customer registrations, transaction patterns, and account activity across different countries. The goal is to enhance financial decision-making, detect anomalies, and optimize services for different customer tiers.

## Objectives
- Analyze the distribution of customers based on registration dates, age, and account status.
- Examine transaction patterns by type (INWARD, OUTWARD, INTERNAL) and monthly trends.
- Identify any irregularities or significant trends in account activity and transaction behaviors.
- Provide insights and recommendations to improve customer engagement and financial operations.

## Data Cleaning Steps
- **Country Code Standardization:** Used the `VLOOKUP` function to convert country codes into full country names for clarity.
- **Date Formatting:** Standardized date columns (`REGDATE`, `TransDate`) to ensure uniformity in analysis.
- **Invalid Data Correction:** Replaced an incorrect date value using the `Find and Replace` function.
- **Handling Missing Values:** Checked and handled missing values in key columns to ensure complete and accurate insights.
- **Formatted Currency Values:** Ensured consistency in transaction amounts for proper aggregation and analysis.

## Key Pivot Analysis Questions
- What is the monthly trend of customer registrations?
- How are customer accounts distributed by status (Active, Blocked, Pending)?
- What is the age distribution of customers, and how does it affect transactions?
- How do transaction amounts vary across different transaction types (INWARD, OUTWARD, INTERNAL)?
- Which countries have the highest number of customers, and how do transaction patterns differ across countries?

## Insights from Analysis
- **Customer Registrations:** The highest number of customer registrations occurred in **September 2024**, with a steady decline afterward.
- **Account Status:** About **92% of accounts are Active**, with **6% blocked** and **2% pending**, indicating a relatively healthy account base.
- **Age Distribution:** The **average customer age is 29**, with most customers being young adults.
- **Transaction Trends:** Transaction amounts showed a **significant spike between November and December 2024**, even though the number of accounts remained stable.
- **Transaction Type Comparison:** **INWARD transactions contributed over 85%** of total transactions but accounted for only **41% of the total transaction amount**, while **INTERNAL transactions had the highest average transaction value**.
- **Country-Based Account Tiers:** Nigeria had the largest number of customers, but most were in **Tier 0 (entry-level)**, suggesting affordability or eligibility barriers for higher tiers.

## Recommendations
- **Improve Customer Onboarding:** Target marketing campaigns around peak registration months to increase customer acquisition.
- **Enhance Fraud Monitoring:** Investigate the November-December transaction spike for potential fraudulent activities or seasonal effects.
- **Encourage High-Value Transactions:** Offer incentives to increase transaction volumes for **INWARD transactions**, which have a lower contribution to total transaction amounts.
- **Improve Tier Upgrades:** Identify and address barriers preventing customers from moving to higher account tiers, especially in Nigeria.
- **Account Activity Monitoring:** Ensure that blocked and pending accounts are reviewed regularly to improve customer retention.
```

