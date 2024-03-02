# Multi-Class Prediction of Obesity Risk

This repository contains Python code for predicting house prices using machine learning techniques. The dataset used for training and testing the model is sourced from the [Kaggle competition Multi-Class Prediction of Obesity Risk.](https://www.kaggle.com/competitions/playground-series-s4e2)

## Project Structure
- Main.ipynb: Jupyter Notebook containing the main code for data preprocessing, exploratory data analysis (EDA), and model training.
- train.csv: Training dataset.
- test.csv: Testing dataset.
- submission.csv: CSV file containing the final predictions for the test dataset using a Random Forest Model.
- submission_tf.csv: CSV file containing the final predictions for the test dataset using a TensorFlow Bidirectional LSTM Model.
- submission_xgb.csv: CSV file containing the final predictions for the test dataset using an XGBoost Model. (This model had the highest score)
- sample_submission.csv: sample of the file containing the final predictions for the test dataset.

## Model Overview
The predictive modeling includes the following steps:

1. Exploratory Data Analysis (EDA): Understanding the dataset's structure, visualizing distributions, and identifying potential outliers.
2. Data Preprocessing: Handling missing values, removing outliers, and creating new features to improve model performance.
3. Feature Engineering: Creating additional relevant features such as BMI.
4. Model Training: Utilizing various regression models including Random Forest, XGBoost, Gradient Boosting, LGBM.
5. Model Evaluation: Evaluating models using accuracy and selecting the best-performing models.
6. Ensemble Learning: Implementing ensemble methods including Voting Regressor to improve predictive accuracy. But that couldn't raise the accuracy result so went with the best performing model which was the XGBoost.

## Results
The final predictions are stored in the submission_xgb.csv file, ready for submission to the Kaggle competition. Placed 2826th out of 3589 submissions in the leaderboard. 

Feel free to explore the Jupyter Notebook for a step-by-step walkthrough of the code and analysis.
