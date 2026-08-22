# Auto Loan ABS Securitisation Analytics

## Project Overview

This repository contains a complete **Auto Loan Asset-Backed Securities (ABS) Securitisation Risk Analytics Solution** developed as part of the **Zetheta Project Work Experience Program**.

The solution leverages **Microsoft Power BI**, **Power Query**, **DAX**, and **Data Modeling** to analyze securitised auto loan portfolios. It provides interactive dashboards for portfolio performance monitoring, delinquency analysis, waterfall and tranche reporting, IFRS 9 Expected Credit Loss (ECL), stress testing, investor reporting, and rating agency reporting.

## Project Objectives

- Design an end-to-end Auto Loan ABS Analytics solution.
- Build an interactive Power BI dashboard for securitisation analytics.
- Develop advanced DAX measures for financial KPIs.
- Analyze portfolio performance and delinquency trends.
- Implement IFRS 9 Expected Credit Loss (ECL) Analytics.
- Perform Stress Testing under multiple economic scenarios.
- Create Waterfall & Tranche Analytics.
- Build Rating Agency Reporting and Data Tape Export.
- Validate Power BI calculations using Microsoft Excel.
- Implement Row-Level Security (RLS) for different business roles.

## Technology Stack

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling
- Microsoft Excel
- CSV Data Sources

## Data Model

The solution integrates multiple datasets:

- Loan Master
- DPD History
- Monthly Loss
- Vintage Data
- Tranche Data
- Stress Testing Data
- Calendar

## Dashboard Modules

### 1. Executive Dashboard
- Total Pool Balance
- Current Balance
- Total Loan Count
- Collection Efficiency
- WAC
- WAM
- WALA
- Weighted Average LTV

### 2. Credit Risk & DPD Analysis
- DPD Distribution
- Delinquency Analysis
- Collection Efficiency## Dashboard Modules

### 1. Executive Dashboard
- Total Pool Balance
- Current Balance
- Total Loan Count
- Collection Efficiency
- Weighted Average Coupon (WAC)
- Weighted Average Maturity (WAM)
- Weighted Average Loan Age (WALA)
- Weighted Average LTV
- Portfolio Composition
- Monthly Balance Trend
- Executive Business Insights

### 2. Credit Risk & DPD Analysis
- DPD Distribution
- Delinquency Analysis
- Collection Efficiency
- State-wise Portfolio Risk
- Vehicle-wise Risk
- Credit Risk Insights

### 3. Monthly Portfolio Performance
- Portfolio Balance Trend
- Monthly Collections
- Loan Performance
- Portfolio Growth
- Monthly Performance Insights

### 4. Vintage Analysis
- Static Pool Performance
- Vintage Curves
- Recovery Trend
- Delinquency Behaviour
- Vintage Performance Insights

### 5. Pool Stratification Analysis
- CIBIL Distribution
- LTV Distribution
- Vehicle Type Analysis
- Geographic Distribution
- Borrower Segmentation

### 6. Waterfall & Tranche Analysis
- Waterfall Allocation
- Tranche Distribution
- Credit Enhancement
- Investor Cash Flow
- Tranche Performance Analysis

### 7. IFRS 9 ECL Analytics
- Expected Credit Loss (ECL)
- Probability of Default (PD)
- Loss Given Default (LGD)
- Exposure at Default (EAD)
- Stage Migration
- IFRS 9 Business Insights

### 8. Stress Testing & Investor Reporting
- Base Scenario
- Moderate Scenario
- Severe Scenario
- Crisis Scenario
- Dynamic PD Multiplier (What-If Parameter)
- Dynamic LGD Multiplier (What-If Parameter)
- Investor Yield Analysis
- Stress Testing Insights

### 9. Rating Agency Reporting
- Pool Summary
- Delinquency Analysis
- Loss & Recovery
- Prepayment Trend
- Waterfall Summary
- Rating Summary

### 10. Data Tape Export
- Rating Agency Data Tape
- Loan-Level Portfolio Information
- Investor Reporting Dataset
- Export Ready Reporting Table

### 11. Loan Details (Drill Through)
- Loan-Level Information
- Borrower Details
- DPD Status
- Vehicle Details
- State-wise Filtering
- Interactive Drill Through Navigation

## Data Model

The solution follows an Industry Standard Star Schema.

### Dimension Tables
- Calendar
- DimBorrower
- DimGeography
- DimServicer

### Fact Tables
- Loan Master
- DPD History
- Monthly Loss
- Vintage Data
- Tranche Data
- Stress Testing Data

## Key Features

- Interactive Power BI Dashboards
- Industry Standard Star Schema
- Advanced DAX Measures
- Power Query Data Transformation
- Power BI Performance Analyzer
- DAX Studio Performance Optimization
- Excel Cross Validation
- IFRS 9 Analytics
- Stress Testing
- Dynamic What-If Parameters
- Drill Through Navigation
- Waterfall Analysis
- Rating Agency Reporting
- Data Tape Export
- Row-Level Security (RLS)
- Executive Business Insights

---

## Validation

All major Power BI KPI calculations were validated using Microsoft Excel, including:

- Total Pool Balance
- Current Balance
- Collection Efficiency
- Average CIBIL Score
- Average DTI
- Credit Enhancement
- PD Multiplier
- LGD Multiplier
- Expected Credit Loss (ECL)
- Current Tranche Balance
- Investor Yield

## Performance Optimization

The Power BI model was optimized using:

- Power BI Performance Analyzer
- DAX Studio Server Timings
- DAX Studio Query Benchmark
- Star Schema Data Modeling
- Optimized DAX Measures

## Project Status

**Completed**

## Author

**Payal Dilip Nikam**

Project Work Experience Program

Zetheta Algorithms Private Limited

## License

This project is shared for educational and portfolio demonstration purposes only.

