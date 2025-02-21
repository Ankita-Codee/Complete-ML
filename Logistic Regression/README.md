# Logistic Regression with Hyperparameter Tuning

This project demonstrates the use of **Logistic Regression** for classification. The dataset is artificially generated using **`make_classification`** from scikit-learn to simulate a binary classification problem. The following steps are performed:

1. **Data Generation**: A synthetic dataset is created with features and labels using the `make_classification` function.
2. **Model Training**: Logistic Regression is applied to the dataset to build a predictive model.
3. **Hyperparameter Tuning**: Hyperparameters of the Logistic Regression model are tuned using **GridSearchCV** and **RandomizedSearchCV** to find the best parameters.
4. **Model Evaluation**: The model is evaluated based on performance metrics such as accuracy.

This approach helps improve model accuracy by selecting the optimal hyperparameters through efficient search strategies.

## Technologies Used
- Python
- Scikit-learn
- Logistic Regression
- GridSearchCV, RandomizedSearchCV
