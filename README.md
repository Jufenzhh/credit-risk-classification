# credit-risk-classification
The purpose of this analysis was to develop machine learning models to predict loan statuses based on the data from the lending.csv.
The data utilized in the dataset was the loan_status, and the goal was to predict whether a loan would be healthy (class 0) or high-risk (class 1)
The analysis was made to build models that effectively distinguish between the two loan categories. 

The logistic regression model trained with oversampled data achieved excellent performance in predicting both "healthy" (class 0) and "high-risk" (class 1) loans. It exhibited a balanced accuracy score of 0.99, indicating very high accuracy considering class imbalance.

There are two models in the notebook. 

Key observations for the Original Data.
- The model appears to predict perfectly the labels of "healthy" and "high-risk" loans.
- Precision and recall scores were perfect at 1.00, suggesting no misclassifications. 
- While the values are perfect at 1.00 for all values, it is important to note that perfect results such as this are highly unusual and can not possibly represent the data.
  
Key observations for the Oversampled data.
- The model correctly predicted most "healthy" and "high-risk" loans.
- Precision and recall scores for class 0 were near perfect, suggesting that the model effectively identified "healthy" loans with minimal misclassifications.
- While precision for class 1 (high-risk loans) was slightly lower due to some false positives, the model demonstrated high recall, indicating effective identification of most "high-risk" loans.

