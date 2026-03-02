# 📊 ML Financial Risk Prediction
## 🧾 Project Overview

The ML Financial Risk Prediction project is a machine learning-based system designed to assess financial risk and predict whether an individual is likely to be classified as high risk. The model helps support smarter lending decisions and credit evaluation processes.

This project explores classification algorithms to analyze financial behavior using demographic and economic indicators.

## 🎯 Objective

Predict financial risk level using machine learning models.

Compare model performance between Logistic Regression and Random Forest classifiers.

Provide a data-driven approach to credit risk assessment.

## 📂 Dataset Description

The dataset contains financial and demographic attributes including:

## 👤 Demographic Features

Age

Gender

Education level

Employment status

Region

## 💰 Financial Features

Monthly income (USD)

Monthly expenses (USD)

Savings (USD)

Loan amount

Loan term (months)

Monthly EMI

Loan interest rate (%)

Debt-to-income ratio

Credit score

Savings-to-income ratio

Expense-to-income ratio

## 🎯 Target Variable

High_Risk → Binary classification target indicating financial risk status.

## 🛠 Data Preprocessing

The following preprocessing steps were applied:

Handling missing values

Encoding categorical variables using one-hot encoding

Feature scaling where necessary

Feature engineering for derived ratios

# 🤖 Machine Learning Models Used
## 📌 Logistic Regression

Used as a baseline linear classification model.

Provides interpretable probability-based predictions.

## 🌳 Random Forest Classifier

Ensemble learning method.

Handles nonlinear relationships effectively.

Improves prediction stability and accuracy.

## 📈 Model Evaluation Metrics

The models were evaluated using:

Accuracy Score

Precision

Recall

F1 Score

Confusion Matrix

## 💻 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Machine Learning Classification Algorithms

## 🚀 Project Workflow

Data collection

Exploratory Data Analysis (EDA)

Feature engineering

Model training

Model evaluation

Prediction testing

## 📌 Installation & Setup
Clone Repository
git clone https: (https://github.com/thatboyremo/ML-Financial-Risk-Prediction)
cd ML-Financial-Risk-Prediction
Install Dependencies
pip install -r requirements.txt
▶️ Usage

Run the training script:

python train.py

Or open the Jupyter Notebook:

jupyter notebook
📊 Results

Logistic Regression and Random Forest models were compared.

Random Forest generally performed better in capturing complex patterns.

📌 Future Improvements

Hyperparameter tuning

Deployment using Flask/Streamlit

Adding more financial features

Improving model interpretability

Testing deep learning approaches

🤝 Contribution

Contributions are welcome. Feel free to fork the repository and submit pull requests.

📜 License

This project is licensed under the MIT License.
