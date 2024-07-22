# Divorce Prediction

## Project Overview
The Divorce Prediction project aims to predict the likelihood of divorce based on various features using machine learning techniques.

## Contents
- `divorce_prediction.ipynb`: Jupyter notebook containing the data analysis and modeling code.
- `DS Project_ Shea Yee_ Divorce Prediction_ 15 June 2024.pdf`: Project report summarizing the findings and methodologies.

## Methodology
1. **Data Collection**: The dataset was sourced from [Kaggle's Divorce Predictor Dataset](https://www.kaggle.com/datasets/rabieelkharoua/split-or-stay-divorce-predictor-dataset/data).
2. **Exploratory Data Analysis (EDA)**: We examined the correlation of each feature with the response variable. This included identifying any single feature with a notably stronger correlation that could potentially predict divorce without the need for further machine learning models.
3. **Model Selection**: Various binary classification models were trained, including logistic regression, support vector machines, decision trees, random forests, and ensemble techniques such as bagging and boosting.
4. **Model Evaluation**: Model performance was evaluated using metrics such as accuracy, precision, and recall, as well as the time required to run each model. Logistic Regression was chosen as the final model for divorce prediction due to its simplicity in implementation and processing efficiency.
5. **Feature Importance**: We examined the importance of features in the best-performing model and assessed model performance with a reduced set of features.

## Insights
- The logistic regression model achieved an accuracy of over 90%, which is considered sufficient for the prediction task.
- Nine key features influencing the prediction were identified, they are nine questions summarized in pdf file attached.
- A robust predictive model has been developed, that accurately identifies at-risk couples early in their relationship. By analyzing comprehensive data, our model provides valuable insights into the factors influencing marital stability and divorce risk, contributing significantly to marital studies and intervention strategies.
