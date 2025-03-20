# 🏥 Kidney Disease Classification

## 📌 Project Overview

This project focuses on predicting kidney disease using machine learning techniques. It involves exploratory data analysis (EDA) and model building using various classification algorithms to achieve accurate predictions.

## 🛠️ Technologies Used

- **Python Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn
- **Machine Learning Models:**
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Gradient Boosting Classifier
  - XGBoost Classifier
  - CatBoost Classifier
  - Extra Trees Classifier
  - LightGBM Classifier
  - GridSearchCV for hyperparameter tuning

## 📊 Dataset and Features

The dataset contains multiple clinical attributes used to predict kidney disease:

```
'age', 'blood_pressure', 'specific_gravity', 'albumin', 'sugar', 'red_blood_cells', 'pus_cell',
'pus_cell_clumps', 'bacteria', 'blood_glucose_random', 'blood_urea', 'serum_creatinine', 'sodium',
'potassium', 'haemoglobin', 'packed_cell_volume', 'white_blood_cell_count', 'red_blood_cell_count',
'hypertension', 'diabetes_mellitus', 'coronary_artery_disease', 'appetite', 'peda_edema',
'aanemia', 'class' (Target Variable)
```

## 📈 Exploratory Data Analysis (EDA)

Performed EDA using Pandas, Matplotlib, and Seaborn to:

- Handle missing values
- Identify correlations
- Visualize distributions
- Detect outliers

## 🚀 Model Building & Evaluation

- Implemented multiple classification models to compare performance.
- Used **GridSearchCV** for hyperparameter tuning.
- Evaluated models using **accuracy, precision, recall, and F1-score**.

## 🔥 Key Findings

- Feature importance analysis highlighted **serum creatinine, blood urea, and hemoglobin** as key predictors.
- **Random Forest and XGBoost** performed best with high accuracy.
- Addressed class imbalance using **SMOTE and stratified sampling**.

## 📊 Model Comparison

To compare model performance, created a DataFrame ranking models by accuracy:

### Model Accuracy Scores:

| Rank | Model                         | Accuracy |
|------|-------------------------------|----------|
| 1    | Stochastic Gradient Boosting  | 99.17%   |
| 2    | Cat Boost                     | 99.17%   |
| 3    | Extra Trees Classifier        | 99.17%   |
| 4    | Random Forest Classifier      | 97.50%   |
| 5    | Gradient Boosting Classifier  | 97.50%   |
| 6    | XgBoost                       | 97.50%   |
| 7    | Decision Tree Classifier      | 94.17%   |
| 8    | KNN                           | 70.83%   |

## 📌 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/RNNivash/Kidney-Disease-Prediction-using-Machine-Learning
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 🎯 Future Improvements

- Implement deep learning models (ANNs)
- Deploy as a web app using Flask or Streamlit
- Optimize hyperparameters using **Bayesian Optimization**

## 📬 Connect with Me

- LinkedIn: [Nivash](https://www.linkedin.com/in/nivash-r-n/)
- Portfolio: [Nivash](https://rnnivash.github.io/My_Port/)
- Email: [hello.nivashinsights@gmail.com](mailto:hello.nivashinsights@gmail.com)

🔍 **Let's leverage data science to make healthcare better!** 🚀

