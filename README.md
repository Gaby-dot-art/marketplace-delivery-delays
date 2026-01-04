# Marketplace Ops: Delivery Delays & Customer Satisfaction

## Overview
Small analytics project focused on marketplace operations, analyzing delivery delays and their impact on customer satisfaction using a public e-commerce dataset.

## Dataset
Public dataset: Olist Brazilian E-Commerce.
Search on Kaggle: "Olist Brazilian E-Commerce Public Dataset".

## Tools
- Python (Pandas, NumPy, Matplotlib, SciPy)
- Jupyter Notebook

## Key Questions
- What percentage of orders are delivered late?
- How do delivery delays affect customer review scores?
- Is the difference statistically significant?

## Method
- Parsed delivery and estimated dates
- Computed delivery delay in days
- Flagged late deliveries
- Compared review scores (on-time vs late)
- Applied Mann–Whitney U test for statistical validation

## Key Findings
- **6.76%** of orders were delivered late
- On-time deliveries average review score: **~4.29**
- Late deliveries average review score: **~2.27**
- The difference is **statistically significant** (p < 0.05)

## Conclusions
Even a small proportion of delayed deliveries can strongly impact customer satisfaction.
This insight highlights the importance of last-mile delivery optimization in marketplaces and e-commerce operations.
