📌 Project Overview

This project builds a Machine Learning regression model to predict the price of diamonds based on their physical and categorical features. The dataset used is the well-known Diamonds dataset, which contains attributes such as carat, cut, color, clarity, and dimensions.

Multiple regression techniques (Linear Regression and Polynomial Regression) were applied and evaluated using performance metrics like RMSE and R² score.

🎯 Objective

The main goal of this project is to:

Analyze relationships between diamond features and price
Build predictive regression models
Compare model performance
Improve prediction accuracy using feature engineering and polynomial transformation
📊 Dataset Information

The dataset includes the following features:

carat → Weight of the diamond
cut → Quality of the cut
color → Diamond color grade
clarity → Clarity level
depth → Total depth percentage
table → Width of top of diamond relative to widest point
x, y, z → Physical dimensions (length, width, depth)
price → Target variable (price of diamond)

Dataset used:
Diamonds Dataset

⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
🧠 Machine Learning Workflow
Data Cleaning & Preprocessing
Encoding Categorical Variables
Feature Scaling using StandardScaler
Train-Test Split
Model Training:
Linear Regression
Polynomial Regression
Model Evaluation:
R² Score
RMSE
📈 Model Performance

The models were evaluated using:

RMSE (Root Mean Squared Error) → Measures prediction error
R² Score → Measures model accuracy

👉 Polynomial Regression improved performance compared to Linear Regression by capturing non-linear relationships in the data.

🚀 Results Summary
Model	RMSE	R² Score
Linear Regression	Higher error	Lower accuracy
Polynomial Regression	Lower error	Better fit
📌 Key Learnings
How to preprocess real-world datasets
Handling categorical + numerical features together
Difference between Linear and Polynomial Regression
Importance of evaluation metrics (RMSE, R²)
Impact of feature engineering on model performance
📂 Project Structure
diamond-price-prediction/
│
├── diamond_model.py
├── dataset.csv
├── README.md
└── requirements.txt
