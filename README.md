# ab-testing-regression-marketing-campaigns

📊 A/B Testing & Regression Analysis on Marketing Campaign Performance
Overview

This project analyzes the effectiveness of different marketing campaign strategies using A/B testing and regression analysis. The goal is to determine whether campaign variants lead to statistically significant differences in customer engagement and conversion outcomes, and to quantify which factors most strongly influence performance.

The analysis combines experimental design, statistical hypothesis testing, and predictive modeling to produce actionable business insights.

🎯 Objectives

Evaluate whether marketing campaign variants produce statistically significant performance differences

Measure lift between control and treatment groups

Identify key drivers of customer response using regression modeling

Translate statistical results into clear business recommendations

🧠 Key Questions

Do different marketing campaigns lead to higher conversion rates?

Is the observed performance difference statistically significant or due to randomness?

Which customer or campaign attributes most strongly influence outcomes?

How confident can decision-makers be in rolling out the winning campaign at scale?

📁 Dataset Description

The dataset contains customer-level marketing campaign data, including:

Campaign group assignment (A/B variants)

Customer demographics and attributes

Engagement indicators

Conversion or response outcomes

Each row represents an individual customer exposed to a specific campaign.

🔬 Methodology
1. Exploratory Data Analysis (EDA)

Assessed data quality, missing values, and distributions

Compared baseline characteristics across campaign groups

Visualized response and conversion patterns

2. A/B Testing

Defined control and treatment groups

Formulated null and alternative hypotheses

Conducted statistical significance testing

Calculated p-values and confidence intervals

Estimated lift and effect size

3. Regression Analysis

Built regression models to isolate campaign impact

Controlled for customer-level variables

Interpreted coefficients to quantify influence

Evaluated model assumptions and fit

📈 Key Findings

Identified statistically significant performance differences between campaign variants

Quantified conversion lift attributable to the winning campaign

Highlighted additional customer attributes that amplify campaign effectiveness

Provided evidence-based guidance for campaign rollout decisions

🧪 Tools & Technologies

Python

Pandas, NumPy – data manipulation

Matplotlib, Seaborn – visualization

SciPy, Statsmodels – hypothesis testing & regression

Jupyter Notebook – analysis workflow

📂 Project Structure
├── marketing_campaign.csv        # Dataset
├── AB Testing (Marketing Campaigns).ipynb
├── README.md

🚀 Business Impact

This analysis demonstrates how data-driven experimentation can:

Reduce guesswork in marketing decisions

Improve ROI by validating campaign effectiveness

Enable confident scaling of high-performing strategies

Bridge the gap between analytics and business strategy

📌 Next Steps

Extend analysis to multi-variant (A/B/C) testing

Add customer lifetime value (CLV) modeling

Automate experiment reporting via dashboards

Test robustness across different customer segments
