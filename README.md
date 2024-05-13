# Churn-Prediction

Data Pre-processing -

1. Checking for NULL and Duplicate values in the dataset.
3. Handled numerical and categorical variables separately in EDA.
4. Univariate Analysis (both Numerical and Categorical Variables)
5. Box plots to determine outliers in the dataset.
6. Bivariate Analysis (Categorical and Numerical Variables against the target variable).

Insights from EDA-

1. 79% of the customers are not churned and 21% of the customers are churned -- Hence dataset was deemed to be imbalanced.
2. Number of males customers are more than female.
3. There are very few customers who has taken 3-4 products.
4. More than 75% customers has credit card.
5. Ratio of active and non-active members are approximately 1.
6. Credit score of customers are negatively skewed.
7. Age is positively skewed.
8. Tenure, Balance and Estimated Salary data are showing non-normal distribution curve.

Feature Engineering and Modelling
1. Encoded Categorical Variables.
2. Performed feature engineering.
3. Train Test Split - Performed Oversampling to handle imbalance in the data.
4. Modeling (Fitted logistic regression model and XGBoost)
5. Performed Cross Validation to get the best value of the hyperparameters and thus create the optimal model.
6. Achieved an accuracy of 87%.
