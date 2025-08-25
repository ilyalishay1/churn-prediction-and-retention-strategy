# churn-prediction-and-retention-strategy
Project Goal:
Customer Churn Prediction: Determine the probability of customer churn.
Audience Segmentation for Discounts: Identify customers for whom discounts will be most effective in retention and profit increase.

Project Stages

1. Data Collection and Preparation
Data Quality Check:
Identify missing values and anomalies.
Clean the dataset by removing duplicates and incorrect records.
Data Processing:
Encode categorical variables.
Normalize numerical variables for consistency in scale.

2. Data Analysis
Conduct statistical analysis to identify key churn risk factors.
Analyze correlations between various segments of main variables and their impact on churn.
Explore correlations between features and the target variable (Churn).
Formulate conclusions based on the analysis.

3. Model Development
Data Splitting:
Split the dataset into training (80%) and testing (20%) sets.
Algorithm Selection:
Choose an appropriate classification model.
Model Evaluation:
Assess model performance using metrics such as ROC-AUC, F1-Score, Precision, and Recall.

4. Identifying Target Audience for Discounts
Load a dataset containing new user information, clean the data, and convert variables to the required format.
Predict customer churn and churn probability for new users.
Identify customers with high and medium churn probabilities.
Further Analysis:
Segment customers based on Tenure, SatisfactionScore, OrderCount, OrderAmountHikeFromLastYear, and DaysSinceLastOrder.
Evaluate the financial viability of discount offers through potential ROI analysis.

5. Developing a Discount Strategy
Define discount amounts based on ROI values.
Determine personalized discount values for each user.
