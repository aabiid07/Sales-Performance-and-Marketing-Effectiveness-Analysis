# Sales-Performance-and-Marketing-Effectiveness-Analysis
## Project Overview

This project involves a comprehensive statistical analysis of a retail dataset  to identify key drivers of sales performance. By evaluating marketing budgets, advertising strategies, and customer behaviors, this study provides actionable insights to optimize marketing allocation and payment strategies.

## Business Problem

A retail company aimed to answer four critical questions:

1. What factors drive higher sales performance? 


2. Does marketing investment significantly impact revenue? 


3. Are certain advertising strategies more effective than others? 


4. Does customer payment behavior influence sales value? 



## Dataset Description

The analysis was performed on a dataset containing 300 observations with the following variables:

* **Categorical:** Region (5 major U.S. cities), Advertising Method (Print, Radio, Social Media, TV), Sales Category (High, Medium, Low), Payment Method, and Customer Type (New, Returning, VIP).

* **Numerical:** Marketing Budget, Online Advertising Spend, Sales Amount, and Store Size.



## Key Findings & Insights

* **Marketing Impact:** Marketing budget has a moderate but statistically significant positive effect on sales. For every 1-unit increase in budget, sales amount increases by 0.310 units.

* **Advertising Effectiveness:** There is a significant difference in sales performance across advertising methods (). Specifically, Social Media advertising resulted in significantly higher sales compared to Print advertising ().

* **Payment Behavior:** While Payment Method is significantly associated with Sales Category (), it does not cause a statistically significant variation in the total Sales Amount.

* **Data Characteristics:** High-value sales dominate total transactions, accounting for 58.3% of the data. Online advertising spend is highly skewed and requires transformation for future modeling.



## Strategic Recommendations

1. **Optimize Marketing Spend:** Since sales increase with the marketing budget, the focus should be on optimizing ROI rather than reducing spend.


2. **Refine Advertising Mix:** Shift allocation toward more effective channels like Social Media while re-evaluating the performance of Print advertising.


3. **Target High-Value Transactions:** Encourage payment methods that are most frequently associated with high-value sales categories.



## Tools Used

* **SPSS:** Used for Exploratory Data Analysis (EDA), normality testing (Kolmogorov-Smirnov & Shapiro-Wilk), and inferential statistics.


* **Statistical Techniques:** Multiple Linear Regression, Simple Linear Regression, One-Way ANOVA with Tukey HSD post hoc tests, and Chi-Square Tests of Association.
