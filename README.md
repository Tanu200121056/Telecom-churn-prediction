# Telecom-churn-prediction
By using the logistic regression model finding the churn in telecom industries
## Business Problem Overview

Title: Customer Churn Prediction and Analysis in the Telecom Industry

Introduction:
The telecommunications industry, marked by fierce competition, experiences an annual churn rate of 15-25%. Retaining existing customers has become paramount due to the high costs associated with acquiring new ones. This project focuses on analyzing customer-level data from a leading telecom company to predict high-risk churn customers and identify crucial indicators of churn.

Defining Churn in Telecom Industry:
Churn prediction varies between postpaid and prepaid payment models. While postpaid customers' churn is directly indicated by their switch, prepaid churn is more complex due to dormant usage. This project employs a usage-based definition for churn, considering prepaid's prevalence in Indian and Southeast Asian markets.

High-Value Customer Churn:
A significant portion of revenue (approximately 80%) in these markets comes from the top 20% of customers, termed high-value customers. Targeting churn reduction among these customers can substantially mitigate revenue loss.

Business Objective and Data:
The dataset spans four consecutive months (June to September), aiming to predict ninth-month churn using data from the initial three months. Understanding customer behavior during churn's three phases (good, action, churn) is crucial for effective prediction.

Customer Behavior During Churn:
Churn isn't an instant decision; it occurs over time. The good phase is when customers are content, followed by the action phase marked by deteriorating experiences. Finally, churn phase, where customers actually leave. The challenge is that during prediction, churn phase data isn't available.

Data Preparation Steps:

1.Derive relevant features based on business understanding.
2.Define high-value customers as those with recharge amounts >= 70th percentile of average recharge in good phase.
3.Tag churners using specific attributes (e.g., zero calls, no mobile internet) in the churn phase.
4.Remove churn phase attributes.

Modeling Approach:

1.Preprocess data (format columns, address missing values).
2.Conduct exploratory analysis for insights.
3.Create new features.
4.Apply PCA for dimensionality reduction due to the high number of attributes.
5.Train models, considering class imbalance, and tune hyperparameters.
6.Evaluate models using appropriate metrics that prioritize churner identification.
7.Choose a model based on evaluation metrics.

Identifying Important Predictor Attributes:

1.Build another model (logistic regression or tree model) to identify significant predictors.
2.Handle multi-collinearity for logistic regression.
3.Visually present key predictors through plots or summary tables.

Recommendation for Managing Churn:
Based on findings, propose strategies for customer churn management.

Conclusion:
This project centers on predicting high-value customer churn in the telecom industry using data-driven techniques. By understanding customer behavior, deriving features, modeling, and identifying key predictors, the aim is to provide actionable insights for churn reduction and business growth. The final submission will be a comprehensive Jupyter notebook encompassing all stages of the analysis.




