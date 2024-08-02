# XGBoost

Introduction
This project focuses on applying boosting algorithms to classify data from the Titanic dataset. The analysis includes implementing and evaluating the performance of XGBoost, a popular boosting algorithm, and comparing it with other models.

Table of Contents
Introduction About the Dataset Data Preprocessing Exploratory Data Analysis (EDA) Implementing Decision Tree Classifier Implementing XGBoost Hyperparameter Tuning Model Performance Evaluation Conclusion

About the Dataset
The Titanic dataset includes the following features:

PassengerId: Unique identifier for each passenger Survived: Survival status (0 = No, 1 = Yes) Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) Name: Name of the passenger Sex: Gender of the passenger Age: Age of the passenger SibSp: Number of siblings/spouses aboard the Titanic Parch: Number of parents/children aboard the Titanic Ticket: Ticket number Fare: Fare paid for the ticket Cabin: Cabin number Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Data Preprocessing
Loading Data:
Loaded the Titanic dataset into a pandas DataFrame for inspection.

Handling Missing Values:
Filled missing values in numerical columns with the mean and in categorical columns with the mode.

Feature Selection:
Selected numerical features for modeling.

Exploratory Data Analysis (EDA)
Descriptive Statistics:
Reviewed the basic statistics and structure of the dataset. Checked for missing values and handled them appropriately.

Implementing Decision Tree Classifier
Data Splitting:
Split the dataset into training and testing sets using an 80-20 split.

Training the Decision Tree Model:
Trained a Decision Tree classifier using the training data. Predicted the survival status for the test data using the trained model.

Model Performance Evaluation:
Calculated the accuracy score of the Decision Tree model to measure its performance.

Implementing XGBoost
Training the XGBoost Model:
Trained an XGBoost classifier using the training data. Predicted the survival status for the test data using the trained model.

Model Performance Evaluation:
Calculated the accuracy score of the XGBoost model to measure its performance.

Hyperparameter Tuning
Grid Search CV:
Performed Grid Search Cross-Validation to find the best hyperparameters for the XGBoost model.

Tuned parameters: n_estimators and max_depth.
Training with Best Parameters:
Trained the XGBoost model with the best parameters obtained from Grid Search.

Evaluated the model's performance using accuracy score.
Model Performance Evaluation
Comparison with Logistic Regression: Trained a Logistic Regression model using the same dataset for comparison. Evaluated the performance of the Logistic Regression model using accuracy score.

Conclusion
The analysis demonstrated the application of boosting algorithms, specifically XGBoost, for classifying data in the Titanic dataset. Key findings include:

The XGBoost classifier provided higher accuracy compared to the baseline Decision Tree classifier and Logistic Regression. Hyperparameter tuning further improved the model's performance. These insights highlight the utility of boosting algorithms in classification tasks and their effectiveness in handling datasets with mixed types of features. This approach can be applied to various scenarios where accurate classification is crucial for decision-making. ​
