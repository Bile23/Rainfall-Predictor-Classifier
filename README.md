# 🌧️ Rain Prediction in Melbourne using Machine Learning
This project builds and evaluates machine learning models to predict whether it will rain today in Melbourne, Australia. Using historical weather data and Scikit-learn pipelines, we compare the performance of two classifiers: RandomForestClassifier and LogisticRegression.

🔍 Project Highlights
End-to-end ML pipeline with Pipeline and GridSearchCV

Data preprocessing using column transformers (handling numeric and categorical features)

Feature importance visualization for model interpretability

Evaluation with classification report and confusion matrix

Comparison based on:

✅ Accuracy

🔢 Number of correct predictions

📈 True Positive Rate (recall) for predicting rain

📊 Results Summary
Accuracy (both models): 83%

Correct Predictions: 1,254 out of 1,512

True Positive Rate (Logistic Regression): 51%

📁 About the Dataset
The original dataset was obtained from Kaggle, and originates from the Australian Government's Bureau of Meteorology. Column descriptions were gathered from the official climate data guide.

The dataset includes daily weather observations from 2008 to 2017 across various Australian locations.
