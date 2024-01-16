# Project Description

## Libraries Used
This project relies on various Python libraries for data analysis and machine learning:
- `numpy`: A library for numerical operations.
- `pandas`: Used for data manipulation and analysis.
- `matplotlib` and `seaborn`: Essential for data visualization.
- `scikit-learn`: Utilized for machine learning tasks, including `KNeighborsClassifier`, `StandardScaler`, and evaluation metrics.

## Step 1: Problem Statement
The project aims to predict whether a user in a social network will make a purchase based on demographic factors such as gender, age, and estimated salary. This prediction is achieved through the implementation of a machine learning model trained on historical data.

## Step 2: Data Gathering
The dataset was obtained from Kaggle and consists of 400 rows and five columns. This dataset serves as the foundation for training and testing the machine learning model.

## Step 3: Exploratory Data Analysis (EDA)
### 3.1 Check for Null Values
An initial check for null values was conducted to ensure data completeness.

### 3.2 Check for Outliers
Outliers were identified through the use of boxplot graphs, providing insights into potential anomalies within the data.

### 3.3 Statistical Values
A comprehensive examination of statistical values, obtained using the `describe` function, provided valuable insights into the central tendencies and spread of the dataset.

### 3.4 Data Information
The `info` function was employed to gather essential information about the dataset, aiding in the identification of object data types and other key attributes.

## Step 4: Feature Engineering
### 4.1 Outlier Detection
A robust outlier detection method using the interquartile range (IQR) was implemented to identify and handle outliers within the dataset.

### 4.2 Label Encoding
The `Gender` column was label encoded to convert categorical data into a numerical format suitable for machine learning algorithms.

### 4.3 Scaling
Feature scaling using `StandardScaler` was applied to ensure uniformity and enhance the performance of the machine learning model.

## Step 5: Model Training
### 5.1 Data Splitting
The dataset was split into features (X) and the target variable (Y) to facilitate model training.

### 5.2 KNN Algorithm
A demonstration model was created using the K-nearest neighbors (KNN) algorithm with an initial k value of 1.

## Step 6: Model Evaluation (Demo Model)
### 6.1 Accuracy
The demo model exhibited 100% accuracy on the training dataset and 84% accuracy on the testing dataset.

### 6.2 Elbow Method
The elbow method was employed to determine the optimal value of k for the KNN algorithm.
![download](https://github.com/Yogendra-Wadkar/Telecom-Customer-Churn-Prediction-Using-Machine-Learning/assets/134367735/0c6cbf0a-0076-4ab7-9174-5bd0eab19908)


### 6.3 For Loop for KNN Models
A for loop was implemented to train various KNN models with different k values, tracking error rates for each model.

### 6.4 Elbow Method Visualization
A visualization graph was generated to illustrate the elbow method and assist in identifying the optimal k value.

## Step 7: Model Evaluation (Final Model)
### 7.1 Optimal K Value
The elbow method revealed an optimal k value of 8 for the final KNN model.

### 7.2 Final Model Accuracy
The final KNN model achieved remarkable accuracy, with 92% on the training dataset and 90% on the testing dataset.

## Step 8: Conclusion
In conclusion, this project successfully addresses the problem of predicting user purchases in a social network through the application of a KNN machine learning model. The detailed exploratory data analysis, robust feature engineering, and thorough model evaluation contribute to the project's effectiveness in making accurate predictions.

