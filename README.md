# Business Operations & KPI Governance Case

**Role fit:** Data Analyst · BI Analyst · Business Analyst · Operations Analyst  
**Skills shown:** Power BI · SQL · DAX · Power Query · KPI Logic · Data Quality · Star Schema · Business Analysis  
**Author:** Serkan Akdemir

## Project Summary

This project analyzes an online retail transaction dataset to demonstrate how raw transaction data can be cleaned, modeled, visualized and validated to support business decisions.

The analysis focuses on:

- Revenue quality
- Customer value
- Cancellation effects
- Product and revenue-line risks
- CustomerID data quality
- SQL validation of Power BI metrics

## Business Question

Why do revenue quality, customer value and operational efficiency develop differently although business activity is visible in the transaction data?

## Final Case Dossier

[View the full PDF dossier](./Akdemir_Skill_Dossier_Business_Operations_Analytics.pdf)

## Dashboard Preview

### 1. Executive Overview

![Executive Overview](./assets/dashboard-1-executive-overview.png)

### 2. Customer & Revenue Deep Dive

![Customer Deep Dive](./assets/dashboard-2-customer-deep-dive.png)

### 3. Product & Cancellation Risk

![Product Cancellation Risk](./assets/dashboard-3-product-cancellation-risk.png)

## Key Findings

- Gross Revenue: approx. 10.64m €
- Net Revenue: approx. 9.75m €
- Adjustment Revenue: approx. -896.81k €
- Cancellation Rate: approx. 14.81%
- Known Customer Revenue: approx. 8.30m €
- Orders without CustomerID Rate: approx. 14.32%
- United Kingdom dominates country-level Net Revenue with approx. 8.19m €

## SQL Validation

Selected dashboard metrics were reproduced with SQL in SQLite to validate the Power BI logic directly on transaction-level data.

SQL checks include:

1. Country Performance
2. Customer Value
3. Product Cancellation Risk
4. Monthly Net Revenue
5. CustomerID Data Quality

[View the SQL validation notebook](./Online_Retail_SQL_Analysis_clean.ipynb)

## Tools Used

- Power BI Service
- Power Query
- DAX
- SQL
- SQLite
- Python / pandas
- Google Colab
- GitHub

## Recommendations

The analysis leads to five main recommendations:

1. Establish Cancellation Value as an operational KPI.
2. Review product and revenue lines with high cancellation value.
3. Improve CustomerID data quality.
4. Monitor top customers by revenue, order frequency and cancellation behavior.
5. Use Power BI dashboard plus SQL checks as a KPI governance process.

## Application Purpose

This repository is part of an application portfolio for analytical roles. It demonstrates practical ability in data preparation, KPI definition, dashboarding, SQL validation and business-oriented interpretation.
