# Alfido Tech — Customer Behavior Analysis

Kaggle source: https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis

## Contents
- `notebooks/alfido_customer_behavior_analysis.ipynb` — Jupyter/Colab analysis
- `reports/Alfido_Tech_Customer_Behavior_Report.pdf` — PDF report
- `visualizations/` — PNG charts
- `data/` — cleaned and aggregated CSV files

## Headline results
- 250,000 transactions
- 49,661 unique customers
- Total recorded purchase amount: 681,346,299
- Average transaction value: 2,725.39
- Repeat-customer share: 96.7%
- Churn-label rate: 20.0%

## Method
Data cleaning → customer-level RFM features → five RFM segments → purchase/category analysis → cohort retention → churn diagnostics.

## Caveat
The supplied churn label is nearly flat across behavioral groups; correlations with RFM variables are close to zero. Use the segments for engagement prioritization, but define a stronger production churn target from explicit inactivity/cancellation events.
