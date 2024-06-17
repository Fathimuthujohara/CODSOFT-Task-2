# CODSOFT-Task-2:
# Titanic Survival Prediction 🚢

This project leverages machine learning to predict the survival of passengers aboard the Titanic using logistic regression. By utilizing a subset of data for hyperparameter tuning, we enhance model performance while reducing computation time. 🧠💡

## Overview

This repository contains all the code and resources needed to predict the survival of Titanic passengers based on various features. Our approach includes the following steps:

### 1. Loading and Preprocessing Data 📊

We start by loading the Titanic dataset and handling missing values to ensure data integrity. Columns that aren't useful for prediction are dropped, and categorical columns are converted to numerical format using one-hot encoding. This preprocessing step sets a solid foundation for accurate predictions.

### 2. Splitting Data ✂️

The data is split into features (`X`) and the target variable (`y`). We further divide the data into training and testing sets, and standardize the features for optimal performance of the gradient boosting model.

### 3. Hyperparameter Tuning 🎛️

To fine-tune our model, we use a smaller subset of the training data for hyperparameter tuning. This is done efficiently with `RandomizedSearchCV`, which searches for the best hyperparameters without exhausting computational resources.

### 4. Model Training 🏋️‍♂️

Using the best parameters identified during hyperparameter tuning, we train the final gradient boosting classifier model on the full training dataset. This ensures that our model is both well-tuned and robust.

### 5. Model Evaluation 📈

We evaluate the model's performance on the test set using metrics such as accuracy, classification report, and confusion matrix. To enhance interpretability, the confusion matrix is visualized using a heatmap, providing clear insights into the model's predictive power.

### 6. Predictions 🔮

Finally, we make predictions and print the first 10 results, showing the actual versus predicted values. This step showcases the practical application and accuracy of our model.

## Results

Our model achieves high accuracy and provides comprehensive performance metrics. The use of hyperparameter tuning on a data subset ensures that we strike a balance between performance and computation time. 🚀

## Visualization

The confusion matrix is visualized using a heatmap for better understanding of model performance.

## Conclusion

This project exemplifies a robust approach to predicting Titanic survival using Gradient Boosting Classifier. By leveraging hyperparameter tuning on a subset of data, we ensure efficient and effective model training. 🏆

