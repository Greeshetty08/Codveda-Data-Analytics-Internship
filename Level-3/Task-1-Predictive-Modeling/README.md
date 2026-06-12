# Customer Churn Prediction using Machine Learning

## Objective

The objective of this project is to build and evaluate machine learning classification models to predict whether a customer is likely to churn based on account information, service usage, and customer interaction data.

## Tools Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## Dataset

The dataset contains customer-related information including:

* State
* Account Length
* Area Code
* International Plan
* Voice Mail Plan
* Call Usage Statistics
* Customer Service Calls
* Churn Status

Two datasets were used:

* churn-bigml-80.csv (Training Dataset)
* churn-bigml-20.csv (Testing Dataset)

## Data Preprocessing

* Loaded training and testing datasets.
* Encoded categorical variables using Label Encoding.
* Separated features and target variable.
* Prepared data for machine learning models.

## Models Implemented

### 1. Logistic Regression

* Accuracy: 85.91%
* Precision: 0.5161
* Recall: 0.1684
* F1 Score: 0.2540

### 2. Decision Tree Classifier

* Accuracy: 91.75%
* Precision: 0.7041
* Recall: 0.7263
* F1 Score: 0.7150

### 3. Random Forest Classifier

* Accuracy: 94.60%
* Precision: 0.9538
* Recall: 0.6526
* F1 Score: 0.7750

## Hyperparameter Tuning

Grid Search Cross Validation was applied to improve the Random Forest model.

### Best Parameters

* max_depth = None
* n_estimators = 100

### Best Cross Validation Score

* 0.9456

## Visualizations

* Confusion Matrix
* Model Performance Comparison

## Results

Among all tested models, the Random Forest Classifier achieved the highest performance with an accuracy of 94.60% and an F1 Score of 0.7750.

## Conclusion

The project successfully predicted customer churn using multiple classification algorithms. The Random Forest model demonstrated superior predictive performance and can be used as an effective tool for identifying customers at risk of leaving the service.

