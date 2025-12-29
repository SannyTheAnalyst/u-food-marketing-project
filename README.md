# U Food Marketing Project

## Overview
This project explores a food marketing dataset to understand customer demographics, purchasing behavior, and campaign response. The goal is to generate actionable insights that could inform segmentation, targeting, and campaign optimization.

## Key Findings (with Visual Evidence)
The findings below are supported by exploratory visuals in  
`notebooks/U Food Marketing Analysis.ipynb`.

- **Income and recency are strong indicators of value**: higher-income customers with more recent purchases generate significantly higher total spend (see *Income Distribution* histogram).
- **Spending is concentrated in a few categories**: *Wine* and *Meat* products account for the largest share of total spend across customers (see *Total Spend by Product Category* bar chart).
- **Household composition matters**: customers without children tend to show higher discretionary spending than households with dependents (supported by spend comparisons across household profiles).
- **Campaign acceptance is low overall**: most customers did not accept prior campaigns, indicating substantial opportunity for improved targeting and personalization (see *Campaign Acceptance* summary/plot).

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
