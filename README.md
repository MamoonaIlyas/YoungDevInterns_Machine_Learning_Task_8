# YoungDevInterns_Machine_Learning_Task_8
 Implement Hyperparameter Tuning  Task: Optimize model hyperparameters.  Details:  Use tools like GridSearchCV or RandomizedSearchCV to find the best hyperparameters for a model.  Evaluate the impact of different hyperparameters on model performance
📌 Overview
This project is part of the YoungDev AI & ML Internship and focuses on optimizing a Logistic Regression model using GridSearchCV. The goal is to classify cereal products into Low, Medium, or High rating categories based on their nutritional information.

📊 Dataset
Source: preprocessed_cereal.csv

Target Variable: rating_class (categorized from original rating column)

Classes: Low, Medium, High

⚙️ Key Steps
Preprocessing

Converted numeric ratings into 3 categories using binning

Encoded target labels using LabelEncoder

Model Definition

Logistic Regression with max_iter=1000

Hyperparameter Tuning
