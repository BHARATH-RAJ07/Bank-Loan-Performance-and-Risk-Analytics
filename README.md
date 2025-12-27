# End-to-End Bank Loan Analytics Project (SQL & Power BI)

An end-to-end Bank Loan Analytics project using SQL Server and Power BI to track loan performance, portfolio risk, and borrower behavior through KPI dashboards, trend analysis, and Good vs Bad loan classification.

---

## Project Overview

This project presents a Bank Loan Performance Analytics Dashboard built using SQL Server and Power BI to analyze lending performance, borrower behavior, and portfolio risk.

The objective is to transform raw loan data into actionable insights that help financial institutions:

- Monitor loan growth and repayments
- Assess overall portfolio quality
- Track credit risk using Good vs Bad loan classification
- Identify trends across time, geography, and borrower attributes

The solution is delivered through three interactive dashboards:

- Summary
- Overview
- Details

---

## Business Problem

Banks handle thousands of loan applications across multiple regions and borrower profiles.  
Without a consolidated analytical view, it becomes difficult to:

- Track loan disbursement and recovery performance
- Monitor credit risk and bad loans
- Identify seasonal and regional lending trends
- Evaluate borrower financial health

This project solves these challenges by providing a centralized BI reporting system for loan analytics.

---

## Tools and Technologies

- SQL Server – Data querying and KPI calculations
- Power BI – Dashboard design and interactive visualizations
- Excel / CSV Dataset – Loan data source

---
## Live Power BI Dashboard
Explore the interactive Power BI report here:  
[View Power BI Dashboard](https://app.powerbi.com/groups/me/reports/1eec8b0e-77ab-48fa-8837-64ca28d54185/a5f3304bbd23d8346e4e?experience=power-bi)


## Dashboard 1: Summary (Executive View)

### Key Performance Indicators

- Total Loan Applications
- Month-to-Date (MTD) Applications
- Month-over-Month (MoM) Growth
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)

### Good vs Bad Loan Analysis

Loans are classified as:

- Good Loans – Fully Paid, Current
- Bad Loans – Charged Off

Metrics tracked:

- Application percentage
- Number of applications
- Funded amount
- Amount received

### Loan Status Grid View

A detailed grid categorized by Loan Status, showing:

- Total applications
- Funded amount
- Amount received
- MTD funded and received amounts
- Average interest rate
- Average DTI

---

## Dashboard 2: Overview (Trend and Distribution Analysis)

### Visual Insights

- Monthly Trend Analysis – Identifies seasonality and growth patterns
- State-wise Lending Analysis – Highlights regional loan concentration
- Loan Term Distribution – 36 vs 60 months comparison
- Employment Length Analysis – Impact of borrower employment history
- Loan Purpose Breakdown – Primary reasons for borrowing
- Home Ownership Analysis – Relationship between ownership and lending

### Metrics Displayed

- Total Loan Applications
- Total Funded Amount
- Total Amount Received

---

## Dashboard 3: Details (Operational View)

### Objective

Provide a granular, record-level view of loan data for operational and analytical deep dives.

### Features

- Loan ID and issue date
- Purpose, grade, and sub-grade
- Home ownership and employment details
- Funded amount and interest rate
- Installment and total amount received
- Fully filterable by State, Grade, and Loan Quality

---

## SQL Logic and Data Modeling

All KPIs and visuals are powered by custom SQL queries, including:

- MTD and PMTD calculations
- Month-over-Month growth analysis
- Good vs Bad loan classification
- Aggregations by date, state, purpose, term, and employment length

### SQL Query Reference Document

Refer to the complete SQL logic used in this project:  
Bank_Loan_SQL_Query

---

## Key Insights

- Over 86 percent of loans are classified as Good Loans, indicating strong portfolio health
- Debt consolidation is the most common loan purpose
- Borrowers with longer employment history show higher application volumes
- 36-month loans dominate the portfolio
- Consistent growth observed in MTD funded and received amounts

---

## Project Outcome

- Delivered an end-to-end loan analytics solution
- Enabled data-driven credit and risk analysis
- Created executive, analytical, and operational dashboards
- Demonstrated strong SQL and Power BI integration

---

## Author

Bharath Raj S  

