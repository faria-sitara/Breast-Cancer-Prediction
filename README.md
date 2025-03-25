# 🧠 Breast Cancer Prediction Using Machine Learning

This project aims to predict whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)** using machine learning models. It leverages a public dataset and various classification algorithms to build an accurate prediction system.

## 📂 Project Overview

Breast cancer is one of the most common cancers worldwide. Early diagnosis plays a crucial role in treatment and survival. In this project, we use features extracted from medical images to predict tumor type.

## 📌 Features Used

The dataset includes several features related to the tumor, such as:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- ...and many more.

## 🧰 Tools & Libraries

- Python
- pandas
- numpy
- matplotlib / seaborn (for visualization)
- scikit-learn (for ML models)
- XGBoost
- missingno (for visualizing missing data)

## ⚙️ Models Trained

We implemented and compared the performance of the following models:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost Classifier

## 📊 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 📈 Results

The best-performing model is identified based on its accuracy and prediction reliability. Visualizations help explain which features are most influential in the predictions.

## 💾 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-prediction.git
   cd breast-cancer-prediction
