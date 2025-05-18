# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset is highly imbalanced and contains transactions over two days. Various preprocessing, analysis, and modeling techniques are applied to distinguish between fraud and non-fraud cases.

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Total Transactions: 284,807
- Fraudulent Transactions: 492
- All features are numeric (float/int), with no missing values.

## 🧠 Workflow

1. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis
   - Correlation heatmap
   - Class imbalance observation

2. **Preprocessing**
   - Feature scaling (StandardScaler on `Amount`)
   - Dropped `Time` feature as it had no major relevance

3. **Modeling**
   - Applied **Random Forest Classifier**
   - Evaluated feature importances
   - Focused on metrics suitable for imbalanced data

4. **Evaluation**
   - Confusion matrix
   - Precision, Recall, F1-Score
   - ROC-AUC score

## 🙌 Credits
Project by Sri – an aspiring Data Scientist exploring AI in creative ways! 
