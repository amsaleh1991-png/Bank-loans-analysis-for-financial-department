# Bank-loans-analysis-for-financial-department
Bank Loan Analytics Dashboard: A comprehensive Power BI solution for visualizing loan performance, risk assessment, and borrower demographics. Gain actionable insights into loan applications, funded amounts, interest rates and debt-to-income ratios to optimize lending strategies and manage portfolio risk effectively Built with Power BI, Power Query
# Bank Loan Analytics Dashboard
[Bank loans Dashboard (2).md](https://github.com/user-attachments/files/26755580/Bank.loans.Dashboard.2.md)


# Bank Loans Analysis Dashboard

## Overview
This project presents a comprehensive Bank Loans Analysis Dashboard designed to monitor and assess the performance of loan portfolios. The dashboard provides a high-level summary of key lending metrics, including total loan applications, funded amounts, and repayment status. By distinguishing between "Good" and "Bad" loans, the analysis offers critical insights into credit risk, borrower demographics, and lending trends, enabling financial institutions to optimize their lending strategies and risk management.

## Data Source
The analysis is based on a detailed dataset of bank loan applications, covering various borrower attributes, loan terms, and repayment outcomes. Specific details regarding the data structure and collection are available within the original Power BI report.

## Tools Used
This Bank Loans Analysis Dashboard and its interactive components were developed using:
*   **Power BI Desktop:** Utilized for data modeling, performance metric calculations (DAX), and the creation of dynamic, multi-page analytical reports.
*   **Power Query:** Used for Extract, Transform, Load (ETL) operations to clean and prepare the raw data.

## Key Findings and Analysis Highlights
The dashboard provides a detailed breakdown of the bank's lending performance across multiple dimensions.

### Overall Lending Metrics
The following schedule summarizes the high-level Key Performance Indicators (KPIs), including Month-to-Date (MTD) figures and Month-over-Month (MoM) growth rates.

| Metric | Value | MTD (Month-to-Date) | MoM (Month-over-Month) |
| :--- | :--- | :--- | :--- |
| **Total Loan Applications** | 38.6K | 4.3K | +6.9% |
| **Total Funded Amount** | $436M | $54M | +13.0% |
| **Total Received Amount** | $473M | $58M | +15.8% |
| **Average Interest Rate** | 12.05% | 12.4% | +3.5% |
| **Average DTI (Debt-to-Income)** | 13.3% | 13.7% | +2.7% |

### Loan Quality Analysis
The dashboard categorizes loans into "Good" and "Bad" based on their repayment status, providing a clear view of portfolio health.

**Good Loans (Includes "Fully Paid" and "Current" loans):**
*   **Applications:** 32K (83.3% of total)
*   **Funded Amount:** $351M
*   **Received Amount:** $412M

**Bad Loans (Includes "Charged Off" loans):**
*   **Applications:** 6K (16.7% of total)
*   **Funded Amount:** $84M
*   **Received Amount:** $61M

### Detailed Loan Status Breakdown
The following schedule provides a granular view of loan performance based on specific statuses.

| Loan Status | Total Applications | Total Funded Amount | Total Amount Received | Average Interest Rate | Average DTI |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Fully Paid** | 32,145 | $351,358,350 | $411,586,256 | 11.64% | 13.2% |
| **Charged Off** | 5,333 | $65,532,225 | $37,284,763 | 13.88% | 14.0% |
| **Current** | 1,098 | $18,866,500 | $24,199,914 | 15.10% | 14.7% |
| **Total** | **38,576** | **$435,757,075** | **$473,070,933** | **12.05%** | **13.3%** |

### Borrower and Loan Characteristics
Analysis of borrower demographics and loan specifics reveals several key trends:

*   **Loan Term:** The majority of loans are for a 36-month term (**28.2K or 73.2%**), compared to 60-month terms (**10.3K or 26.8%**).
*   **Employment Length:** Borrowers with **10+ years** of employment represent the largest segment of applicants (**8.9K**), followed by those with < 1 year (4.6K).
*   **Loan Purpose:** **Debt consolidation** is the primary reason for loan applications (**18K**), followed by credit card refinancing (5K) and home improvement (3K).
*   **Home Ownership:** Most applicants either **Rent (18.4K)** or have a **Mortgage (17.2K)**, with a very small minority owning their homes outright.

## Visualizations
The Power BI report includes three main sections, each designed for a specific analytical purpose:

1.  **Summary:** High-level KPIs, MTD/MoM metrics, and loan status breakdowns (Good vs. Bad loans).
2.  **Overview:** Trends over time (Monthly line charts), geographical distribution (State map), and categorical analysis (Term, Purpose, Home Ownership, Employment Length).
3.  **Details:** A granular grid view of individual loan records, including IDs, grades, sub-grades, issue dates, and specific financial terms.

## How to Use/Explore
To interact with the full dashboard and explore the data in detail, please refer to the original Power BI file (`.pbix`). This README serves as a summary of the project's key findings and analytical scope. Users can utilize the interactive slicers (e.g., State, Grade, Loan Status) within the Power BI environment to dynamically filter and analyze specific data segments.

## Conclusion
This Bank Loans Analysis Dashboard provides a robust framework for evaluating lending health. By tracking MTD and MoM changes alongside long-term trends and detailed categorical breakdowns, the organization can identify emerging risks, understand borrower behavior, and uncover opportunities in its loan portfolio, ensuring sustainable financial growth.
