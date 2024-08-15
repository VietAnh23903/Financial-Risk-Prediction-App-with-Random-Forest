inancial Risk Prediction App with Random Forest

Overview

This project implements a financial risk prediction application using a Random Forest classifier. The application predicts whether a person is at financial risk based on various input features such as income, age, loan amount, credit score, employment details, and more. image

![image](https://github.com/user-attachments/assets/193b3d69-c7b2-49d8-9b12-0d2e1f07f322)



MachineLearning.py

![image](https://github.com/user-attachments/assets/7ba2e39b-df4d-4d21-bc45-1b2430013680)


datatrain.csv

Key Features:

  Data Preprocessing: The project includes data preprocessing steps such as handling categorical data and scaling numerical features using scikit-learn.
  Model Training: Utilizes a Random Forest classifier to train the predictive model on a dataset containing labeled financial data.
  Model Evaluation: Evaluates the model using metrics like accuracy, precision, and recall to assess its performance.
  Visualization: Includes visualizations of decision trees, ROC curves, feature importance, and AUC scores using matplotlib and PyQt.

Usage:

  Data Input: Users can input various financial attributes through a GUI interface.
  Prediction: Based on user input, the app predicts whether the individual is at financial risk or not.
  Results Display: The predicted risk status and evaluation scores (accuracy, precision, recall) are displayed to the user.

Technologies Used:

  Python, PyQt for GUI development
  scikit-learn for machine learning tasks (Random Forest classifier, metrics evaluation)
  matplotlib for data visualization (decision tree plots, ROC curves)
  Firebase Realtime Database for data storage and retrieval

Future Improvements:

  Implementing additional machine learning algorithms for comparison.
  Enhancing the GUI for a more intuitive user experience.
  Integrating real-time data updates using Firebase for dynamic predictions.
