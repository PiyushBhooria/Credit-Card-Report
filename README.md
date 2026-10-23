# Credit Card Financial Analytics - Power BI Dashboard

## Project Overview
This project provides a comprehensive Power BI analysis of credit card operations, focusing on customer demographics and transaction trends. By analyzing revenue streams, expenditure categories, and user profiles, the dashboard offers actionable financial insights to optimize card offerings, target marketing efforts, and understand consumer spending behaviors.

## Datasets Used
The analysis is built upon four primary datasets containing transactional and customer demographic data:
*   `customer.csv`: Comprehensive customer profile and demographic data.
*   `credit_card.csv`: Core credit card transaction and revenue data. 
*   `cust_add.csv`: Additional or updated customer metrics.
*   `cc_add.csv`: Additional credit card operational metrics.

## Dashboards & Key Insights

### 1. Credit Card Customer Report 
**File Reference:** `Credit Card Customer Dashboard.png`

This dashboard segments revenue generation by various customer demographics, providing a clear picture of the most profitable user profiles.

**Key Metrics:**
*   **Total Revenue:** $57M
*   **Total Interest Earned:** $8M
*   **Total Customer Income Base:** $588M
*   **Customer Satisfaction Score (CSS):** 3.19

**Demographic Insights:**
*   **Age:** The 40-50 age bracket is the highest revenue driver, contributing ~$25M in total revenue, followed closely by the 50-60 age group.
*   **Occupation:** 'Businessman' is the most profitable occupation segment ($17.6M), followed by 'White-collar' workers ($10.2M) and Government employees ($8.3M).
*   **Geography:** Texas (TX), New York (NY), and California (CA) are the top 3 performing states, each generating approximately $13M in revenue with a fairly even split between male and female customers.
*   **Income & Marital Status:** High-income individuals and married customers represent the largest revenue pools within their respective categories.

### 2. Credit Card Transaction Report
**File Reference:** `Credit Card Transaction Dahsboard.png`

This dashboard analyzes spending habits, transaction methods, and card performance across the fiscal year.

**Key Metrics:**
*   **Total Revenue:** $57M
*   **Total Transaction Amount:** $45.5M
*   **Total Transaction Count:** 667.2K

**Transaction Insights:**
*   **Card Tier Performance:** The 'Blue' card category is overwhelmingly the most popular, generating the vast majority of the revenue ($47.1M) and transaction volume.
*   **Expenditure Types:** Customers spend the most on 'Bills' ($14M), followed by 'Entertainment' ($10M) and 'Fuel' ($10M). Travel represents the lowest major category at $6M.
*   **Transaction Method:** Physical 'Swipe' transactions remain the dominant payment method ($36M), followed by 'Chip' ($17M). Online transactions currently account for the smallest portion ($4M).
*   **Quarterly Trends:** Revenue and transaction counts show steady growth throughout the year, peaking in Q4 with $14.5M in revenue and 173.2K transactions.

## Strategic Takeaways
1.  **Targeted Marketing:** Marketing campaigns should heavily target individuals in the 40-50 age bracket, specifically focusing on business owners and white-collar professionals in TX, NY, and CA.
2.  **Product Development:** With the 'Blue' card dominating revenue, there is an opportunity to either increase benefits for the Blue tier to drive loyalty or restructure Silver/Gold/Platinum tiers to incentivize upgrades.
3.  **Digital Adoption:** Online transaction volumes are remarkably low ($4M). Promoting digital wallet integrations or offering online spending cash-back incentives could drive e-commerce growth.

## How to Use This Repository
1.  Download the `.pbix` file and the associated `.csv` dataset files.
2.  Open the `.pbix` file using **Power BI Desktop**.
3.  If prompted to refresh the data, ensure the file paths in the Power Query Editor point to the local directory where you saved the `.csv` files.
4.  Navigate through the tabs at the bottom to view the *Customer* and *Transaction* reports.
