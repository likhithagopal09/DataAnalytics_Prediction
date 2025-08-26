Student Performance Prediction using Logistic Regression

Project Overview:

This project predicts whether a student will Pass or Fail based on two factors:
-Study Hours
-Attendance
The model is built using Logistic Regression and evaluated with accuracy and confusion matrix.

Dataset

-Total Records: 200 students
-Features:
StudyHours → Number of hours spent studying
Attendance → Attendance percentage
-Target:
Pass → 1 (Pass), 0 (Fail)

Steps in the Project

-Import required libraries
-Load the dataset
-Explore dataset (shape, missing values, value counts)
-Split data into train and test sets
-Build pipeline (StandardScaler + Logistic Regression)
-Train the model
-Make predictions
-Evaluate the model (accuracy and confusion matrix)
-Interpret results
-Summarize insights

Results

-Accuracy: Around 80% (may vary slightly)
-Confusion Matrix: Shows true positives, true negatives, false positives, and false negatives
-Key Insights:
Higher study hours and better attendance increase the chances of passing
Low study hours or poor attendance increase the chances of failing

Tech Stack

-Python
-Pandas
-NumPy
-Scikit-learn
-Matplotlib / Seaborn

Future Work

-Experiment with other machine learning models (Decision Trees, Random Forests, SVM)
-Add more features such as parental education or test preparation
-Perform hyperparameter tuning to improve accuracy

Acknowledgements

-Dataset: Custom simulated student performance dataset
-Libraries: scikit-learn, pandas, numpy

BY AUTHOR - Likhitha Gopal
