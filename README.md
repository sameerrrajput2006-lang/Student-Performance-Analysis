Student Performance Analysis and Prediction System

Project Overview

The Student Performance Analysis and Prediction System is a Python-based Machine Learning project designed to analyze students' academic performance and predict their examination scores using Linear Regression.

The project explores how study hours, attendance, and previous examination scores relate to students' final performance.

Objectives

- Analyze students' academic performance.
- Identify relationships between academic factors and examination scores.
- Visualize important performance trends.
- Build a Machine Learning model to predict examination scores.
- Evaluate the model using standard regression metrics.

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

The dataset contains academic and other factors associated with student performance.

Important features used:

- Hours Studied
- Attendance
- Previous Scores
- Exam Score (Target Variable)

Dataset Source: https://www.kaggle.com/datasets/lainguyn123/student-performance-factors

Project Workflow

1. Data Collection
2. Data Loading and Inspection
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Train-Test Split
7. Linear Regression Model Development
8. Model Evaluation
9. Cross-Validation
10. Feature Coefficient Analysis

Machine Learning Algorithm

Linear Regression

The model uses the following input features:

- Hours Studied
- Attendance
- Previous Scores

It predicts the student's examination score.

Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- 5-Fold Cross-Validation

Repository Structure

Student-Performance-Analysis/
│
├── data/
├── notebooks/
│   └── student_performance_analysis.ipynb
│
├── outputs/
│   ├── visualizations/
│   └── evaluation_results/
│
├── screenshots/
├── README.md
├── requirements.txt
└── .gitignore

Results

The model's performance is evaluated using MAE, RMSE, R² Score, and cross-validation. Detailed results and visualizations are available in the "outputs/" folder.

How to Run the Project

1. Clone this repository.
2. Install the required libraries:
   "pip install -r requirements.txt"
3. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
4. Load the dataset from the "data/" folder.
5. Run the notebook cells sequentially.

Conclusion

This project demonstrates how Python and Machine Learning can be used to analyze academic performance, identify relevant patterns, and predict examination scores.

---

Project: Minor Project – Student Performance Analysis and Prediction System
Course: BCA (Artificial Intelligence and Machine Learning)
