# Superstore Profitability Analysis

Analyzed the impact of discount strategies on profitability using the Superstore dataset to identify loss-making products, high-risk discount levels, and opportunities to improve business performance.

## Project Overview

This project analyzes Superstore sales data to evaluate business profitability, identify loss-making products, and assess the impact of discount strategies on company performance.

Using Python for data preparation and Tableau for visualization, the analysis aims to uncover key profit drivers and provide actionable business recommendations to improve profitability.

## Business Questions

1. How do region, segment, category, and sub-category contribute to profitability?
2. How do discount levels affect profit performance?
3. Which products contribute most to company losses?
4. What business actions can improve overall profitability?

## Tools & Technologies

- Python
- Pandas
- NumPy
- Tableau
- GitHub

## Dataset Information

- Dataset: Sample Superstore
- Total Records: 9,994
- Total Features: 21

## Data Preparation

The following preprocessing steps were performed:

- Missing value validation
- Duplicate checking
- Data type conversion
- Feature engineering:
  - Profit Margin
  - Loss Transaction
  - Discount Category

## Key Findings

- The company generated $286.4K profit from $2.30M sales, achieving a 12% profit margin.
- 26.31% of transactions (1,318 orders) resulted in losses.
- The West Region generated the highest profit contribution.
- Technology was the most profitable category.
- Tables (-$17.7K) and Bookcases (-$3.5K) were the primary loss-making sub-categories.
- Discounts above 30% were strongly associated with negative profits.

## Business Recommendations

- Cap discounts at 30% to reduce loss-making transactions.
- Review pricing strategies for Tables and Bookcases.
- Prioritize promotions for profitable Technology products.
- Investigate products with high sales but negative profits.
- Apply successful sales strategies from the West Region to lower-performing regions.

## Dashboard Preview

<img width="1606" height="928" alt="SuperStore_Dasboard" src="https://github.com/user-attachments/assets/4794f63f-2547-48d1-9c71-2d12c04414a8" />

## Repository Structure

```text
superstore-profitability-analysis
│
├── data/
├── notebook/
├── dashboard/
├── output/
└── report/
```

## Author

Rafif Pradipta Bagaskara

Data Analyst Portfolio Project
