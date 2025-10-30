📈 Linear Regression Model — Predicting Sales from Advertising Data
📘 Project Overview

This project demonstrates how to build and evaluate a Linear Regression model using Python’s scikit-learn library. The model predicts sales revenue based on radio advertising expenditure, showcasing how simple linear regression can reveal the relationship between two continuous variables.

🚀 Objective

To predict company sales based on the amount spent on radio advertisements using a simple, interpretable regression model.

🧠 Key Steps

Import Libraries — pandas, numpy, matplotlib, and scikit-learn.

Load Dataset — Read the dataset Advertising.csv containing marketing data.

Data Visualization — Visualize the relationship between radio advertising spend and sales.

Data Splitting — Split the dataset into training and test sets using train_test_split().

Model Training — Train a linear regression model using LinearRegression().

Prediction & Evaluation — Predict on test data and visualize the regression line.

Model Interpretation — Extract the slope (m) and intercept (b) to form the regression equation:

Sales
=
𝑚
×
Radio
+
𝑏
Sales=m×Radio+b
📊 Visualization

The notebook includes a scatter plot showing the data distribution and the fitted regression line, illustrating how the model fits the observed data.

🧩 Technologies Used

Python 3

Pandas — Data manipulation and analysis

NumPy — Numerical computation

Matplotlib — Data visualization

scikit-learn — Machine learning and model training

📂 Dataset

The dataset used is Advertising.csv, which contains columns like:

Column	Description
TV	TV advertising budget
Radio	Radio advertising budget
Newspaper	Newspaper advertising budget
Sales	Units sold / Revenue generated

In this project, only the Radio and Sales columns were used for building the regression model.

🧮 Regression Formula

After training, the linear model can be represented as:

Sales
=
𝑚
×
Radio
+
𝑏
Sales=m×Radio+b

where m is the coefficient (slope) and b is the intercept obtained from the model.

📈 Results

The fitted regression line shows a positive correlation between radio ad spending and sales.

The model provides an interpretable equation for predicting future sales values.

💡 Future Enhancements

Extend the model to Multiple Linear Regression using TV and Newspaper columns.

Add performance metrics such as R² score, MAE, and RMSE.

Deploy the model using Streamlit or Flask for web-based prediction.

🧑‍💻 Author

Kuldeep Vishwakarma
