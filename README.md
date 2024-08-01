## Ames House Price Prediction
This project aims to predict house prices in Ames, Iowa using various regression techniques. The dataset utilized for this project can be accessed through the following link:

https://www.kaggle.com/datasets/nabilabdul/ames-house-price-prediction-regression?select=data_description.txt

## Models Used
Five different regression models were applied to predict house prices:

### Linear Regression: 
A fundamental regression model that assumes a linear relationship between the input features and the target variable.
### Ridge Regression: 
A type of linear regression that includes regularization to address potential multicollinearity in the dataset.
### Lasso Regression: 
Similar to ridge regression but uses L1 regularization to enhance feature selection by shrinking some coefficients to zero.
### Partial Least Squares (PLS): 
A method that projects the predictors and responses into a new space to maximize the covariance between them.
### Principal Component Analysis (PCA): 
A dimensionality reduction technique used to preprocess the data before applying regression models, aiming to improve performance and interpretability.

### Model Comparison
After applying the above models, a comparison was made using a graph to evaluate their performance. The graph demonstrates that among the models tested, Lasso Regression performed the best, achieving the highest accuracy in predicting house prices.

### Explanation
Linear Regression provided a baseline performance.
Ridge Regression improved upon this baseline by addressing multicollinearity but did not outperform Lasso.
Lasso Regression outperformed the other models due to its ability to perform both regularization and feature selection, leading to a more precise and simplified model.
Partial Least Squares and Principal Component Analysis helped in reducing dimensionality and handling collinearity but were less effective compared to Lasso in this specific case.
The graph clearly highlights that Lasso Regression achieved the best results, making it the preferred model for predicting house prices in this dataset.
