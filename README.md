A machine learning model built in Python to predict student academic marks based on study hours, attendance, and past performance.

Project Overview
This project uses Linear Regression to analyze key factors affecting student grades and predict final test scores. It follows a complete machine learning pipeline: data cleaning, feature analysis, model training, and performance evaluation.

Tech Stack & Tools
Language: Python

Platform: Google Colab / Jupyter Notebook

Libraries:

pandas — Data loading and manipulation

numpy — Numerical operations

matplotlib & seaborn — Data visualization & correlation plots

scikit-learn — Model building, splitting dataset, and evaluation metrics

Project Workflow
Data Preprocessing: Handled missing values, encoded non-numeric features, and structured the dataset.

Exploratory Data Analysis (EDA): Plotted scatter plots and heatmaps to inspect relationships between study habits and marks.

Model Training: Split the dataset into 80% training and 20% testing sets using train_test_split, then fitted LinearRegression().

Evaluation: Measured prediction accuracy using standard metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score
