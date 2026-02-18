# Credit Risk Analysis & Portfolio Performance Dashboard

## Project Overview

This project analyzes a structured loan portfolio dataset to build a data-driven Credit Risk Dashboard.

The objective is to identify key drivers of loan defaults, segment borrower risk profiles, and optimize lending strategy using structured financial analysis.

The dashboard enables:

- Default rate monitoring  
- Risk segmentation analysis  
- Interest rate and pricing evaluation  
- Loan term risk comparison  
- Data-driven underwriting decisions  

This project transforms raw loan-level data into actionable financial insights to improve portfolio stability and risk-adjusted returns.

---

## Dataset Summary

- Dataset Type: Loan Portfolio Dataset  
- Total Records: ~6,000+ loans  
- Primary Unit: Loan-level observation  
- Time Variable: Issue Date (Issue Year extracted)  

---

## Data Dictionary (Key Fields)

| Feature | Description |
|----------|-------------|
| loan_status | Final loan outcome (Fully Paid / Charged Off) |
| default_flag | Binary default indicator (1 = Default, 0 = Non-default) |
| fico_range_low / high | Borrower credit score range |
| fico_mid | Midpoint of FICO range |
| fico_bucket | Categorized credit score segments |
| int_rate_clean | Numeric interest rate |
| int_rate_bucket | Interest rate segmentation |
| dti | Debt-to-Income ratio |
| dti_bucket | Categorized DTI groups |
| term_numeric | Loan tenure (36 / 60 months) |
| annual_inc | Borrower annual income |
| verification_status | Income verification level |
| grade / sub_grade | Credit grade assigned |
| purpose | Loan purpose category |
| issue_year | Extracted loan issuance year |

---

## Analytical Focus Areas

1. Default Rate Analysis  
   Evaluated default concentration across FICO, DTI, interest rate, and loan term.

2. Risk Segmentation  
   Identified high-risk borrower segments using structured bucketization.

3. Pricing and Term Impact  
   Analyzed the effect of 36 vs 60-month loans and higher interest rates on default probability.

4. Verification and Income Impact  
   Studied how income verification influences loan performance.

5. Portfolio Trend Analysis  
   Tracked issuance and default patterns over time.

---

## Key Performance Indicators (KPIs)

- Overall Default Rate  
- Default Rate by FICO Bucket  
- Default Rate by DTI Bucket  
- Default Rate by Loan Term  
- Interest Rate vs Default Ratio  
- Risk Segment Contribution (%)  

---

## Data Cleaning and Feature Engineering

- Converted interest rate from percentage to numeric format  
- Created default_flag from loan_status  
- Calculated fico_mid  
- Created segmentation buckets (FICO, DTI, Interest Rate)  
- Extracted issue_year from issue date  
- Removed inconsistent or incomplete records  

All transformations were performed using Google Sheets formulas and pivot tables.

---

## Intended Outcome

The final dashboard provides:

- Clear visualization of default concentration  
- Identification of high-risk borrower segments  
- Risk-based pricing insights  
- Portfolio monitoring framework  
- Data-backed underwriting recommendations  

---

## Project Status

Completed  
Dashboard Implemented  
Risk Segmentation and KPI Analysis Delivered  

---

## Core Objective

To improve credit decision-making by identifying risk concentration and enabling proactive portfolio management through structured financial analysis.
