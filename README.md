# SyriaTel-
## Overview
This project aims to predict customer churn for SyriaTel, a telecommunications company. Customer churn refers to customers discontinuing their services, which directly impacts revenue and long-term profitability. By analyzing customer behavior and service usage data, we develop machine learning models to identify customers at high risk of churning, enabling proactive retention strategies.

## Business and Data Understanding
### Stakeholder Audience
The primary stakeholders are SyriaTel's management and marketing teams who need to:
* Reduce customer churn rate.
* Improve customer retention.
* Optimize pricing strategies.
* Increase overall profitability.
### Dataset
The dataset contains 3,333 customer records with 21 features including:
* Demographic information (state, area code).
* Account details (account length, international plan, voice mail plan).
* Usage patterns (day/eve/night minutes, calls, charges).
* Customer service interactions.
* Target variable: churn (0 = stayed, 1 = left).

Key insights from initial analysis:
* The dataset is imbalanced with only 14.5% churned customers (483 out of 3,333).
* Features like customer service calls, total day charge, and total day minutes show higher correlation with churn.
* Categorical features (international plan, voice mail plan) may influence churn behavior.
