# U Food Marketing Project

## Overview
This project explores a food marketing dataset to understand customer demographics, purchasing behavior, and campaign response. The goal is to generate actionable insights that could inform segmentation, targeting, and campaign optimization.

## Key Findings
- Customers with higher income and lower recency tend to generate significantly higher total spend.
- Wine and meat products account for the largest share of customer spending across all segments.
- Households without children show higher average discretionary spend than those with dependents.
- Campaign acceptance rates remain low overall, suggesting opportunities for better targeting and personalization.

## Business Impact
Insights from this analysis can help marketing teams:
- Identify high-value customer segments for targeted campaigns
- Optimize product category focus based on spend concentration
- Improve campaign efficiency by aligning offers with customer behavior
- Reduce marketing waste by focusing on customers most likely to respond

## Visual Analysis
The analysis notebook includes exploratory visualizations such as:
- Income distribution and spending behavior
- Product category contribution to total spend
- Campaign response rates by customer profile
These visuals are used to support segmentation and campaign strategy recommendations.

## Project Status & Roadmap
- [x] Data loading and validation
- [x] Initial exploratory data analysis
- [ ] Data cleaning and outlier treatment
- [ ] Customer segmentation
- [ ] Campaign response modeling
- [ ] Final business recommendations


## Repository Structure
- `data/` — dataset file(s)
- `scripts/` — Python scripts (data loading, utilities)
- `notebooks/` — analysis notebook(s) and EDA

## Dataset
File: `data/u_food_marketing.csv`

The dataset includes customer attributes (e.g., income, household composition), recency and purchase activity across product categories, and historical campaign response indicators.

## How to Run (Local)
### Prerequisites
- Python 3.x
- pandas

Install dependencies:
```bash
pip install pandas
