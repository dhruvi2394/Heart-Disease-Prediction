# Heart Disease Prediction using Logistic Regression

This project aims to predict the likelihood of heart disease in patients using a **Logistic Regression** model. It is a beginner-friendly project implemented in **Google Colab**, using a publicly available dataset from Kaggle.

## 📌 Project Overview

- Built in **Google Colab** using Python
- Applies **Logistic Regression** to predict heart disease likelihood
- Evaluates model performance using **Accuracy Score**, **Mean Squared Error (MSE)** and **R² Score**
- Includes visualizations for correlation, feature relationships, and model predictions

## 📊 Dataset

- Source: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Dataset contains 14 attributes including:
  - `age`, `sex`, `cp` (chest pain type), `chol` (cholesterol), `thalach` (max heart rate), etc.
- Target variable: `target` (0 = no disease, 1 = disease)

## ⚙️ Technology Stack

- **Google Colab**
- **Python**
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

## 🔍 Visualizations

- **Correlation Heatmap** to identify feature importance
- **Actual vs Predicted** chart to interpret model performance
- **Scatter & classification comparison** to show prediction trends

## 🤖 Model Used

- **Linear Regression**
  - Used to predict binary target (0 or 1)
  - Performance measured using:
    - **Accuracy Score**
    - **Mean Squared Error (MSE)**
    - **R² Score**

## 📈 Sample Evaluation Output
-Accuracy Socre: 0.8512 Mean Squared Error: 0.1211 R² Score: 0.7023

## 🧪 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload or mount the `heart.csv` dataset
3. Run all cells sequentially
4. Review metrics and plots to analyze model behavior

## 📌 Results

- Logistic Regression is a simple method that gave decent results on this binary classification task.
- Visualizations showed a good match between predictions and actual values in many cases, but it's not perfect for classification.
- This project provides a learning foundation in feature analysis and ML evaluation.

## 🔮 Future Scope

- Use **classification algorithms** like Linear Regression, Random Forest, or SVM
- Deploy the model in a basic **streamlit web app**
- Explore hyperparameter tuning and feature engineering

## 🔗 References

- Dataset: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- scikit-learn documentation: https://scikit-learn.org/
- matplotlib & seaborn documentation

---

> ⚠️ **Disclaimer**: This is an academic project for learning purposes. It is not intended for real medical use.

