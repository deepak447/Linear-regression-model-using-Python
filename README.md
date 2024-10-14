# Linear-regression-model-using-Python
**Salary Prediction Model**

This project aims to develop a machine learning model that can predict employee salaries using various features and techniques. The model is intended to assist HR departments in making informed compensation decisions and ensure consistency and fairness in salary practices.

**Data and Features**

The model was trained on a dataset containing information about employees, including:

* College attended
* City of residence
* Previous CTC (cost to company)
* Previous job change count
* Graduation marks
* Experience (in months)
* Role (manager or non-manager)

**Model Selection and Evaluation**

Multiple regression models were explored and evaluated, including Linear Regression, Ridge Regression, Lasso Regression, K-Nearest Neighbors, Decision Tree, Random Forest, and Gradient Boosting. The models were evaluated based on their R-squared score and Mean Absolute Error (MAE) on a held-out test set.

**Results**

The best performing model was the **Random Forest Regression model** when all features were used. This model achieved an R-squared score of 0.6144 and an MAE of 6759.25.

When only highly correlated features were used, the **K-Nearest Neighbors Regression model** performed the best. It achieved an R-squared score of 0.6256 and an MAE of 6654.64.

**Conclusions**

The Random Forest Regression and K-Nearest Neighbors Regression models are suitable for predicting employee salaries based on the given features. The choice of model may depend on the specific requirements and priorities of the organization, such as the desired balance between accuracy and interpretability.

**Potential Improvements**

To further improve the model's performance, the following steps could be considered:

* Tuning the hyperparameters of the models
* Adding more relevant features to the dataset
* Exploring different model architectures, such as gradient boosted trees or neural networks
* Addressing potential biases or outliers in the data

**Usage**

The model can be used to predict employee salaries by providing the necessary features as input. The predicted salary can be used to inform salary negotiation, compensation planning, and other HR-related decisions.
