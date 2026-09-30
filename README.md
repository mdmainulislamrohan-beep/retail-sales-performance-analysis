# Retail Sales Performance Analysis

## Project Overview

This project analyses retail transaction data to evaluate sales performance, profitability, regional performance and the impact of discounting.

The objective is to identify key business trends, underperforming areas and opportunities to improve profitability.

## Business Questions

1. How have sales changed over time?
2. Which product categories and sub-categories generate the most profit?
3. Which regions perform best?
4. How does discounting affect profitability?
5. Which individual products generate the highest profits and losses?

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

## Key KPIs

- **Total Sales:** $2.33 million
- **Total Profit:** $292,296.81
- **Total Orders:** 5,111
- **Total Customers:** 804
- **Overall Profit Margin:** 12.56%

## Key Findings

- Sales increased by approximately **50.9% from 2023 to 2026**, despite a small decline in 2024.
- **Technology** was the most profitable category, while **Furniture** generated much weaker profit relative to its sales.
- **Tables** were the largest loss-making sub-category, generating approximately **$208,020 in sales** but about **$17,753 in losses**.
- The **West** region had the strongest profitability, while **Central** had the lowest profit margin at approximately **7.9%**.
- Central also had the highest average discount, at approximately **24.1%**.
- Discounts of **30% or more** were predominantly associated with negative overall profit margins.
- The strongest individual profit contributor was the **Canon imageCLASS 2200 Advanced Copier**.
- The largest individual loss came from the **Cubify CubeX 3D Printer Double Head Print**.

## Business Recommendations

1. Review discount policies, particularly discounts of 30% or more.
2. Investigate the pricing and cost structure of loss-making Table products.
3. Review underperforming product groups in the Central region.
4. Protect and expand high-performing categories such as Technology.
5. Monitor product-level profitability rather than relying on sales revenue alone.

## Repository Contents

- `retail_sales_analysis.ipynb` — complete analysis notebook
- `sample_-_superstore.xls` — source dataset

## Limitations

This is a descriptive exploratory analysis. Relationships identified in the data, such as the association between higher discounts and lower profitability, should not be interpreted as causal without additional modelling or experimental evidence.
