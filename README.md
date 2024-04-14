# Company Bankruptcy Prediction

Welcome to the Company Bankruptcy Prediction project repository! This project aims to predict the likelihood of a company going bankrupt using machine learning techniques. The provided code implements Random Forest and Logistic Regression models to classify companies into bankrupt and non-bankrupt categories based on various financial features.

## Overview

In this project, the following steps are performed:

1. **Data Preprocessing**: Cleaning of the dataset by removing columns with missing values and separate features from the target variable.

2. **Data Splitting**: Splitting of the data into training and testing sets using a standard 80-20 split.

3. **Feature Scaling**: Standardizing the features using `StandardScaler` to ensure that all features contribute equally to the model.

4. **Model Training and Evaluation**:
   - **Random Forest**: Training a Random Forest classifier on the training data and evaluate its accuracy on the test data.
   - **Logistic Regression**: Training a Logistic Regression classifier on the standardized training data and evaluate its accuracy on the standardized test data.

## Usage

To use this project:

1. Clone or download the repository to your local machine.
2. Ensure you have the necessary libraries installed.
3. Run the provided Python script or Jupyter Notebook to preprocess the data, train the models, and evaluate the performance.

## Dataset

The dataset used in this project was obtained from Kaggle. It contains financial features of companies, along with a binary target variable indicating bankruptcy status.


## Notebooks

- `Assignment_4.ipynb`: Jupyter Notebook containing the code implementation. You can run this notebook in Google Colab or any Jupyter Notebook environment.

## Results

- **Random Forest Accuracy**: 96.77%
- **Logistic Regression Accuracy**: 96.48%

## Conclusion

Both Random Forest and Logistic Regression models show promising results in predicting company bankruptcy. Further tuning and optimization of the models could potentially improve performance.
