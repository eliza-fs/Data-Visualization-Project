# Bank Customer Churn Dashboard (Tableau)

Group project for Data Visualization, BINUS University (4-person team). This is the visualization follow-up to the [Bank Customer Churn Analysis](https://github.com/eliza-fs/Data-Analytics-Project) (Data Analytics) project.

## Live Dashboard

**View the interactive dashboard on Tableau Public:**
https://public.tableau.com/app/profile/elizaveta.susanto/viz/BankCustomerChurnAnalysis_17823840201330/Dashboard4?publish=yes
https://public.tableau.com/app/profile/elizaveta.susanto/viz/Dashboard21_17823842948050/Dashboard4?publish=yes
https://public.tableau.com/app/profile/elizaveta.susanto/viz/UASDataVisualization_17829963366460/Dashboard?publish=yes

## Overview

Banks hold large customer datasets with many variables, which makes churn patterns hard to spot in raw tables and hard to communicate to non-technical decision makers. This project turns the Bank Customer Churn dataset (~10K customers, 20.4% churn) into interactive Tableau dashboards that show which customer segments are most at risk of leaving.

## My Role

Designed the churn trend chart and KPI cards in the Tableau dashboard.

## Tech Stack

Tableau (dashboard), Python (data preprocessing)

## Dashboard Contents

- KPI cards: total customers and overall churn rate
- Churn trend by tenure
- Customer count and churn rate by country
- Balance vs churn
- Churn rate by age group

## Key Insights

- **Germany has about double the churn rate** of France and Spain (32.5% vs ~16%), and the gap persists even when comparing customers with similar profiles, which points to market-specific factors.
- **Age is the strongest churn predictor** (correlation 0.29), with churn peaking among customers aged 50-55.
- **Country and age reinforce each other:** German customers aged 45-60 churn at 67%, the highest-risk segment in the dataset.
- **High balances are associated with higher churn**, but the correlation is weak (0.12), so balance amplifies other patterns rather than driving churn alone.
- **Tenure is nearly uncorrelated with churn** (-0.014), so long-time customers are not automatically loyal.

## Dataset

Bank Customer Churn Prediction dataset from Kaggle (9,996 records, 12 columns). Add the link and check the license on the Kaggle page before redistributing the file.

## Report

The full report (in Indonesian) is available in [`report/`](report/).
