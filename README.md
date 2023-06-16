# Predicting Stroke
 Predicting Stroke Cases using Logistic Regression

`
# Predicting Stroke Cases using Logistic Regression

## Introduction
This project uses the Logistic Regression algorithm to predict stroke cases based on various features such as age, gender, smoking status, etc. The dataset used in this project is from Kaggle (https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

## Dependencies
This project requires the following dependencies:

- pandas
- numpy
- scikit-learn

## Usage
To use this project, you need to follow these steps:

1. 1. Import the required libraries.

2. Download the dataset from Kaggle and save it as 'stroke.csv' in the same directory as the code.
3. Run the code.

## Code Explanation
The code first loads the dataset using pandas and removes missing values. It then encodes the categorical variables using LabelEncoder, which converts categories into numerical values. The categorical variables that need to be encoded are 'gender', 'ever_married', 'work_type', 'Residence_type', and 'smoking_status'.

The code then splits the dataset into features (X) and target (y), standardizes the features using mean normalization, and splits the data into training and testing sets using train_test_split from scikit-learn. It uses 20% of the data for testing and sets the random state to 0 for reproducibility.

The code then fits the Logistic Regression model on the training data and makes predictions on the testing data using predict method. It evaluates the performance of the model using accuracy_score from scikit-learn, which calculates the proportion of correctly classified instances.

Finally, the code prints the accuracy score of the model on the testing data.

## Conclusion
This project demonstrates how to use Logistic Regression to predict stroke cases based on various features. It shows how to encode categorical variables, standardize features, split the data into training and testing sets, fit the model, make predictions, and evaluate the performance of the model using accuracy score.

