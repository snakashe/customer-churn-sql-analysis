# Customer Churn & Retention Analysis — SQL

## Overview
SQL-based analysis of 10,000 bank customer records to identify churn 
patterns, segment customers by risk tier, and quantify retention signals.

## Key Techniques
- CTEs (WITH clauses) for multi-step logic
- Window functions (ROW_NUMBER, RANK, NTILE, AVG OVER)
- CASE WHEN for customer segmentation and risk scoring
- Subqueries to compare churned vs retained customer profiles
- GROUP BY + HAVING for cohort and product analysis

## Key Findings
- Customers with 3+ products churn significantly more than single-product holders
- Germany has the highest churn rate across all geographies
- Customers with complaints AND satisfaction score ≤ 2 represent the highest-risk segment
- High-balance customers who churn represent the greatest revenue risk

## Dataset
Bank customer churn dataset — 10,000 records with attributes including 
credit score, geography, tenure, balance, complaints, and card type.


