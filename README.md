# CreditRiskPrediction
Using Machine Learning Techniques to analyse several variables and predict if the client will default his/her credit payment in the next month. 

# Models
- Logistic Regression
- Rpart
- Random Forest
- Gradient Boosting
- Neural Network

# Results

Model | Test MSE | Accuracy | ROC
| ------------- | ------------- | ------------- | ------------- |
Logistic Regression | 0.144 |  0.823 | 0.713
Logistic Regression(LASSO) | 0.144 | 0.822 |0.712
Logistic Regression(Rpart) | 0.145 | 0.826 | 0.699
Decision Tree (Anova) | 0.135 | 0.826 | 0.748
Bagged Trees (ntree = 5000, mtry = 23) | 0.133 | 0.826 | 0.748
Random Forest (ntree = 5000, mtry = 7) | 0.133 | 0.826 | 0.769
GBM (CV) | 0.132 | 0.826 | 0.776
GBM (OOB) | 0.133 | 0.827 | 0.771
Neural Network (w/o Feature Selection) | 0.178 | 0.822 | 0.762
Neural Network (w/ Feature Selection) | 0.177 | 0.823 | 0.761
