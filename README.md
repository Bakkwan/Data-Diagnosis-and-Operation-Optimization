# Data Diagnosis and Operation Optimization

## Project Overview

This project analyzes 96,478 business records using SQL and Power BI to identify operational issues, evaluate customer value, and validate data quality.

The objective is to transform raw business data into actionable insights through data diagnosis and operational analysis.

---

## Project Objectives

- Diagnose factors affecting customer satisfaction
- Evaluate operational efficiency
- Identify high-value customer groups
- Validate abnormal data and improve analysis reliability
- Provide optimization recommendations based on data findings

---

## Dataset Overview

| Metric | Value |
|----------|----------|
| Customers | 93,358 |
| Orders | 96,478 |
| GMV | 13.22M |
| Average Order Value | 137.04 |

---

## Analysis Framework

### 1. Operational Efficiency Diagnosis

Analyze the relationship between delivery performance and customer satisfaction.

**Finding**

- Orders delayed more than 7 days received an average rating of 1.70.
- On-time orders received an average rating of 4.29.
- Delivery delay was identified as a major factor affecting customer experience.

**Recommendation**

- Establish delivery warning thresholds.
- Trigger customer service intervention for high-risk delayed orders.

---

### 2. Customer Value Analysis

RFM model was applied to segment customers based on recency, frequency and monetary value.

**Finding**

- 25.2% high-value customers contributed 49.9% of total revenue.
- Average spending of high-value customers was 5.7 times higher than low-value customers.

**Recommendation**

- Strengthen retention strategies for high-value customers.
- Improve conversion of potential customers through targeted campaigns.

---

### 3. Data Quality Validation

During analysis, several abnormal rating results were detected.

**Validation Process**

- Verify sample completeness.
- Investigate extreme values.
- Check sample size sufficiency.

**Finding**

Most abnormal results were caused by insufficient sample size instead of actual business issues.

**Outcome**

Potential misjudgments were avoided through data validation procedures.

---

### 4. Dashboard Development

Power BI dashboard was built for:

- KPI monitoring
- Operational diagnosis
- Customer segmentation
- Regional and category analysis

---

## Key Insights

### Customer Satisfaction

Delivery delay significantly reduces customer ratings.

### Customer Value

A small portion of customers contributes nearly half of total revenue.

### Data Reliability

Data validation is essential before drawing business conclusions.

---

## Tech Stack

- SQL (SQLite)
- Power BI
- Excel
- Data Cleaning
- RFM Analysis
- Business Diagnosis

---

## Dashboard Preview

images/dashboard_overview.png

---

## Repository Structure

```text
Data-Diagnosis-and-Operation-Optimization

├── README.md
├── dashboard
│   └── Operation_Dashboard.pbix

├── report
│   └── Project_Summary.pdf

├── sql
│   └── analysis.sql

├── images
│   └── dashboard_overview.png
