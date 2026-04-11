# Task 1: Predictive Modeling (Customer Churn Classification)
### Level 3 (Advanced)
## Project Objective
The goal of this task was to develop an advanced classification model to predict customer churn. 
By identifying patterns in usage and service history, this model allows the business to proactively target at-risk customers with retention strategies before they leave the service.

## Technical Workflow
**Data Consolidation:** Combined the 80% and 20% Churn-BigML datasets to create a comprehensive population for analysis (3,333 records).

**Feature Engineering:** Encoded categorical features like International plan and Voice mail plan.

Applied StandardScaler to normalize numerical data, ensuring high-volume metrics didn't bias the model.

**Model Comparison:** Evaluated Logistic Regression as a baseline and Random Forest as the advanced champion model.

**Optimization:** Utilized GridSearchCV with 5-fold cross-validation to tune hyperparameters, finding the optimal balance between model depth and estimator count.

## Key Performance Metrics
**Accuracy:** Improved from a baseline of 87% to a final optimized 95%.

**Precision:** High precision ensures that marketing resources are not wasted on loyal customers misidentified as "churn risks."

**Top Predictors:** Usage volume (Total Day Minutes) and customer frustration (Customer Service Calls) were identified as the strongest indicators of future churn.

## Business Insights
**The "Frustration" Threshold:** Customers reaching their 4th service call have a significantly higher probability of leaving.

**Retention Focus:** High-usage customers are the most likely to churn, suggesting they are sensitive to pricing or looking for better-tailored high-volume plans.

## Files in this Folder
**Codveda_Level3_Task1_PredictiveModeling.ipynb:** The complete Jupyter Notebook with code, GridSearch, and visualizations.

**churn-bigml-80.csv & churn-bigml-20.csv:** The source datasets used for modeling.
