# BigBasket-analysis-in-python
 
Data Loading and Exploration
- Loads a dataset (df_bb) from a CSV file containing BigBasket product data.
Data Preprocessing
- Splits the data into features (X) and target (y) variables, categorizing y into bins of low, medium, and high prices.
Model Training and Evaluation
- Applies several regression and classification algorithms:
	- Linear Regression, Ridge Regression, Lasso Regression for price prediction (sale_price).
	- Logistic Regression, Decision Tree Regression, Decision Tree Classification, SVM with Polynomial Kernel, and SVM with RBF Kernel for categorizing price into low, medium, or high.

Model Evaluation Metrics
- Computes Mean Squared Error (MSE) for regression models (Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regression).
- Computes Accuracy and prints Classification Reports for classification models (Logistic Regression, Decision Tree Classification, SVM Polynomial Kernel, SVM RBF Kernel).

Model Selection
- Identifies the best performing model based on the lowest MSE (for regression) or highest accuracy (for classification).
