# 💎 Diamond Price Prediction

This project aims to build a predictive model that estimates the price of diamonds using machine learning techniques and exploratory data analysis (EDA).

---

## 📌 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering & Preprocessing](#feature-engineering--preprocessing)
- [Model Building](#model-building)
- [Evaluation Metrics](#evaluation-metrics)
- [Future Scope](#future-scope)
- [Conclusion](#conclusion)

---

## 🔍 Overview

Diamond pricing is complex and influenced by many factors like carat, cut, color, clarity, and dimensions. This project uses machine learning to predict diamond prices based on these features.

---

## ❓ Problem Statement

The goal is to create a regression model that can accurately predict the price of a diamond given its attributes.

---

## 📚 Dataset


**Features**:
- **Categorical**: `cut`, `color`, `clarity`
- **Numerical**: `carat`, `depth`, `table`, `x`, `y`, `z`
- **Target**: `price`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis

- Inspected data types and null values
- Visualized categorical feature distributions
- Analyzed feature correlations with the target variable
- Identified outliers and data anomalies

---

## ⚙️ Feature Engineering & Preprocessing

- Removed invalid entries (e.g., rows with zero dimensions)
- One-hot encoded categorical variables
- Standardized numerical columns

---

## 🤖 Model Building

- Trained a regression model using **Random Forest Regressor**
- Tuned hyperparameters using `GridSearchCV`
- Saved the final model in two formats:
  - `model.pkl` using `pickle`
  - `model.joblib` using `joblib`

---

## 📊 Evaluation Metrics

The performance of the Random Forest Regressor was evaluated using:

- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**

### 📌 Results:
- **Training MSE**: `0.01`
- **Training R²**: `0.993` ✅
- **Testing MSE**: `0.02`
- **Testing R²**: `0.982` ✅

These results indicate that the model performs exceptionally well on both training and unseen test data, with minimal overfitting.

---

## 🔮 Future Scope

- 🚀 **Model Enhancement**: Explore ensemble methods or deep learning techniques to further refine accuracy.
- 🧠 **Feature Expansion**: Incorporate additional features or external data (e.g., market trends) to improve predictions.
- 🌐 **Real-time Predictions**: Develop a web application or API for real-time diamond price predictions.
- 🔄 **Automation & Pipelines**: Integrate automated data preprocessing pipelines and continuous model retraining as new data arrives.
- ☁️ **Deployment**: Investigate deploying the model to cloud platforms for scalability and accessibility.

---

## ✅ Conclusion

🔥 **Model Performance**  
The **Random Forest Regressor** demonstrated **outstanding predictive accuracy**, achieving:
- **Training R²**: `0.993`
- **Testing R²**: `0.982`

💡 **Why It Worked Well**  
Random Forest was ideal for this dataset due to its ability to:
- Handle **nonlinear relationships**
- Capture **feature interactions** effectively
- Minimize overfitting with built-in **bagging**

🛠️ **Key Success Factors**
- Robust **EDA and outlier handling**
- Smart **feature engineering**
- Hyperparameter tuning using **GridSearchCV**

📦 The final model was saved in both `.pkl` and `.joblib` formats for reuse and deployment.

---
