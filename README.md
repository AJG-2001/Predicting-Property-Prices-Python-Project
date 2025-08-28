# **Predicting Property Prices**

📌 Project Overview

This project applies machine learning techniques to predict real estate property prices using the Property Sales 2007–2019 dataset from Kaggle. The primary objective is to compare model performance using metrics like RMSE and R², while extracting actionable insights for real estate professionals and investors
.

🔎 Dataset

Source: Kaggle – HTAG Holdings, Property Sales 2007–2019

Size: 135,000+ residential real estate transactions in a single region.

Versions Used:

Raw Dataset: Transaction-level data (price, property features, sale date).

MA Dataset: Aggregated quarterly version for smoothed trend analysis (time series).

🛠️ Methodology
Data Preprocessing

Removed missing values & outliers.

Encoded categorical variables (label + one-hot encoding).

Train-test split: 80/20 for validation.

Descriptive Statistics & Insights

Median Prices:

4-bedroom houses → $650K

5-bedroom houses → $805K

2-bedroom units → $405K

3-bedroom units → $530K

5-bedroom units → $1.22M (likely outliers due to low sample size).

Trends:

House prices rose from $505K (2007) → $680K (2018), dipping slightly to $660K in 2019.

Unit prices peaked in 2010, then declined to ~$382.5K by 2019.

Houses consistently outperformed units across all bedroom counts
.

Time Series Observations

2007–2010: Initial growth.

2011–2015: Stabilization.

2016–2019: Peak correction.

Macro cycles visible around 2008 (financial crisis) and 2017
.

Correlation Analysis

Bedrooms ↔ Price: r = 0.48 (moderate correlation).

Postcode ↔ Price: r = 0.43 (location matters).

Year ↔ Price: r = 0.17 (weak temporal impact).

🤖 Machine Learning Models

Random Forest Regressor

Linear Regression

Gradient Boosting

Evaluation Metrics: RMSE, R²

Outcome: Ensemble methods (Random Forest, Gradient Boosting) outperformed simple linear models, highlighting the non-linear nature of property price drivers.

📊 Key Visualizations

Boxplots: Price distributions by property type & bedrooms.

Line Graphs: Median price trends (2007–2019).

Correlation Heatmap: Feature relationships with price.

Smoothed Trend Curves: Long-term macro cycles in property values
.

📂 Deliverables

FINAL_A2_AI.ipynb – Python notebook with analysis, preprocessing, and modeling.

PP A2 AI.pptx – 10-slide presentation summarizing findings.

README.md – This documentation.

🚀 Key Takeaways

Houses outperform units consistently, with higher appreciation rates.

Bedrooms & location are the strongest predictors of property prices.

Temporal factors alone have limited predictive power.

Ensemble ML models provide the best accuracy for price prediction.

📜 References

HTAG Holdings. (n.d.). Property sales [Data set]. Kaggle. https://www.kaggle.com/datasets/htagholdings/property-sales
 

OpenAI. (2024). ChatGPT (July 2024 version) [Large language model]. https://chat.openai.com/
