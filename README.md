⚽ Football Match Outcome & Goal Difference Prediction
Predicting football match outcomes has long been a challenging and fascinating problem in sports analytics. In this project, we tackle two key tasks:

Goal Difference Prediction – a regression task to estimate the score difference between two teams.

Match Outcome Prediction – a classification task to determine whether the home team will lose.

We use a variety of features including team averages, playing styles, aggression, and home advantage to train machine learning models.

🧠 Models Used
Goal Difference Prediction:
- Linear Regression
- Random Forest Regressor
Home Team Loss Prediction:
-Logistic Regression (with PCA)
-Support Vector Classifier (SVC) – linear & RBF kernels
-Random Forest Classifier
-Dimensionality reduction via PCA was also explored to evaluate its impact on model performance.

📈 Key Findings
Random Forest consistently outperforms other models for classification.

For regression, Linear Regression delivers competitive results despite its simplicity.

🚀 How to Use
Clone this repository:

bash
```
git clone https://github.com/sidak706/Football-goal-difference-and-match-winner-prediction.git
cd Football-goal-difference-and-match-winner-prediction
```
Open and run Code.ipynb. It includes all preprocessing and modeling steps.

Note: Data preprocessing is time-consuming. To skip it, use the provided preprocessed dataset:

match_data.csv – ready-to-use dataset for training and evaluation

📄 Report

The report (Analysis_Report.pdf) provides detailed insights into feature selection, model performance, and evaluation metrics.
