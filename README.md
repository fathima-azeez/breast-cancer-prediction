# Breast Cancer Classification Using Machine Learning

This project aims to classify breast cancer tumors as benign or malignant using various supervised machine learning algorithms on the Breast Cancer Wisconsin dataset.

## 📊 Dataset

- **Source:** Breast Cancer Wisconsin Diagnostic Dataset
- **Entries:** 569 samples
- **Features:** 30 numerical features
- **Missing Values:** None

## 🔍 Objective

To compare the performance of different machine learning models and determine which is most effective for accurate and reliable breast cancer diagnosis.

## 🧠 Models Used

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost (with hyperparameter tuning)

## ⚙️ Methods

- Exploratory Data Analysis (EDA)
- Feature Selection
- Model Training
- Hyperparameter Tuning (GridSearchCV for XGBoost)
- Evaluation using metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC AUC

## 📈 Results Summary

| Model             | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|------------------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.965   | 0.953     | 0.953  | 0.953    | 0.997   |
| Random Forest     | 0.956   | 0.952     | 0.930  | 0.941    | 0.995   |
| SVM               | 0.947   | 0.951     | 0.907  | 0.929    | 0.997   |
| XGBoost (Tuned)   | 0.947   | 0.951     | 0.907  | 0.929    | 0.996   |

## 🧪 Requirements

- Python 3.x
- scikit-learn
- pandas
- matplotlib
- seaborn
- xgboost
- jupyter (optional for notebooks)

Install dependencies using:

```bash
pip install -r requirements.txt
