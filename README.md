# heart_disease_uci
# 🫀 Heart Disease Classification using UCI Dataset

This project aims to predict the presence of heart disease using machine learning models based on the [UCI Heart Disease dataset](https://archive.ics.uci.edu/dataset/45/heart+disease).

 Project Overview

Heart disease is a leading cause of death globally. Early diagnosis through data-driven methods can significantly improve outcomes. This project applies various classification algorithms to predict the presence or absence of heart disease using patient clinical data.

---

 Dataset

The dataset used is a cleaned version of the **UCI Heart Disease** dataset containing:
- ✅ 920 patient records
- ✅ 15 features (age, sex, chest pain type, cholesterol, etc.)
- ✅ 1 target variable (`num` — indicating heart disease severity)

Target transformation
- `0`: No heart disease
- `1`: Presence of heart disease (any level above 0 is considered positive)

---

 Workflow

1. **Data Preprocessing**
   - Handling missing values (mean/mode imputation)
   - Label encoding categorical variables
   - Standard scaling of numerical features
   - Binary conversion of the target variable

2. **Model Training**
   Applied the following 10 ML classifiers:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)
   - Naive Bayes
   - Gradient Boosting
   - AdaBoost
   - XGBoost
   - LightGBM

3. Evaluation
   - Accuracy
   - Confusion Matrix
   - Classification Report
   - Bar graph comparison of model performance

---

 Results

The models were compared using accuracy as the evaluation metric. The best-performing models (based on this dataset) were:
 [Insert best models here once you run it, e.g., XGBoost, Random Forest, etc.]


 Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- xgboost
- lightgbm

Install dependencies using:

```bash
pip install -r requirements.txt
