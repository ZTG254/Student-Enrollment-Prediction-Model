Student Enrollment Prediction Model
This repository contains a machine learning model designed to predict student enrollment and identify students who may need additional support to graduate. Using historical enrollment data, academic records, and demographic information, this project leverages a Random Forest Classifier to predict the likelihood of a student enrolling in a program.

Project Overview
Objective: Develop a predictive model to identify students likely to enroll and those needing extra support to graduate.
Data Sources: Includes historical enrollment records, academic performance, and demographic data.
Key Features: Age, GPA, Attendance Rate, Prior Dropouts, Family Income, Parent Education, Major, and Extracurricular involvement.
Model Pipeline
Data Preprocessing:
Encodes categorical variables (e.g., Gender, Family Income).
Scales numerical features for optimized model performance.
Model Training: Trains a Random Forest Classifier to handle complex, non-linear relationships in the data.
Evaluation Metrics:
Accuracy Score
Classification Report (Precision, Recall, F1-score)
Confusion Matrix
Results
The model provides insights into student enrollment trends and helps institutions make data-driven decisions to support at-risk students.
How to Use
Clone the repository and run the Jupyter notebook or Python script to preprocess the data, train the model, and evaluate its performance.
Future Improvements
Incorporate additional features (e.g., financial aid status, high school performance).
Test with other algorithms (e.g., XGBoost, Neural Networks) to improve accuracy.
Requirements
Python 3.x
pandas, scikit-learn, numpy
This project is intended to aid educational institutions by providing actionable insights based on student data. Contributions and improvements are welcome!

