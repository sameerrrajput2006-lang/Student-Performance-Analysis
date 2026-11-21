Student Performance Analysis and Prediction System

Project Overview

This project uses Python and Machine Learning to analyze student academic performance and predict examination scores based on selected academic factors.

The system uses Linear Regression to predict exam scores using:

- Hours Studied
- Attendance
- Previous Scores

Objectives

- Analyze student performance data.
- Perform data cleaning and preprocessing.
- Visualize academic trends and relationships.
- Build a Linear Regression prediction model.
- Evaluate model performance using standard regression metrics.

Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

Dataset

Dataset: Student Performance Factors

Source: https://www.kaggle.com/datasets/lainguyn123/student-performance-factors

Machine Learning Model

Algorithm: Linear Regression

Input Features: Hours Studied, Attendance, Previous Scores

Target Variable: Exam Score

Model Evaluation Results

Metric| Result
MAE| 1.359207
RMSE| 2.310471
R² Score| 0.622338
Average Cross-Validation R²| 0.572816

Feature Coefficients

Feature| Coefficient
Hours Studied| 0.287498
Attendance| 0.199134
Previous Scores| 0.047464

Project Visualizations

The project includes:

- Study Hours Analysis
- Attendance vs Exam Score
- Score Distribution
- Correlation Heatmap
- Actual vs Predicted Exam Scores
- Feature Coefficient Analysis

Project Structure

Student-Performance-Analysis/
│
├── data/
│   └── StudentPerformanceFactors.csv
│
├── notebooks/
│   └── student_performance_analysis.ipynb
│
├── outputs/
│   ├── visualizations/
│   └── evaluation_results/
│
├── screenshots/
│
├── Project_Report.pdf
├── requirements.txt
└── README.md

Conclusion

The project demonstrates how data analysis and machine learning can be used to study academic performance and estimate examination scores. The Linear Regression model achieved an R² score of 0.622338 on the test dataset.

Author

Sameer
Course: Artificial Intelligence and Machine Learning
Roll Number: AIML-A6/SEP-11823
