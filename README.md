# Predict Wine Quality with Regularization

## Project Overview

This project focuses on predicting the quality of red wine using the Wine Quality Dataset from the UCI Machine Learning Repository. The dataset has been modified to classify wine quality into two categories: good (rating > 5) and bad (rating <= 5). The main objectives of this project are to:

1. Implement different logistic regression classifiers.
2. Identify the best ridge-regularized classifier through hyperparameter tuning.
3. Implement a tuned lasso-regularized feature selection method.

## Data Description

The dataset consists of 11 input variables derived from physicochemical tests and one output variable for quality:

### Input Variables:
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**

### Output Variable:
- **Quality**: 0 for bad and 1 for good

## Project Steps

1. **Data Preprocessing**: 
   - Load and explore the dataset.
   - Handle missing values and normalize the input features.

2. **Logistic Regression Classifiers**: 
   - Implement multiple logistic regression classifiers to predict wine quality.
   - Evaluate the performance of these classifiers using appropriate metrics such as accuracy, precision, and recall.

3. **Ridge-Regularized Classifier**:
   - Apply ridge regularization to the logistic regression model to prevent overfitting.
   - Perform hyperparameter tuning to find the best regularization strength.
   - Evaluate the performance of the tuned ridge-regularized classifier.

4. **Lasso-Regularized Feature Selection**:
   - Implement lasso regularization for feature selection.
   - Tune the regularization parameter to identify the most relevant features.
   - Assess the impact of feature selection on model performance.

5. **Comparison and Analysis**:
   - Compare the results of the different logistic regression models.
   - Analyze the effectiveness of ridge and lasso regularizations in improving model performance and feature selection.

## Conclusion

This project demonstrates the application of logistic regression with regularization techniques to classify the quality of red wine. By using ridge and lasso regularizations, the project aims to enhance the model's performance and identify key features contributing to wine quality.
