# 🧠 Hypothyroidism Classification Project

This project explores machine learning classification techniques to predict hypothyroidism using a medical dataset. Hypothyroidism is a condition where the thyroid gland is underactive, leading to numerous health problems. By analyzing a dataset of medical features, this project aims to provide accurate predictions of hypothyroidism diagnosis and explore feature importance for better insights.

## 📋 Project Overview

The dataset includes several attributes related to patient health records, including TSH levels, T3, TT4, and other hormonal readings. The goal of this project is to apply different classification algorithms to predict whether a patient has hypothyroidism or not.

### 📊 Key Features:
- **Feature Selection**: Identifies the most important medical features contributing to the diagnosis of hypothyroidism.
- **Classification Models**: Implements various classification models such as:
  - Logistic Regression
  - Decision Trees
  - Random Forests
  - Support Vector Machines (SVM)
  - K-Nearest Neighbors (KNN)
- **Data Preprocessing**: Handles missing values, normalization, and feature scaling to improve model performance.
- **Evaluation Metrics**: Uses accuracy, precision, recall, F1-score, and confusion matrices to assess model performance.

## 🧬 Methodology

1. **Data Preprocessing**: 
   - Loaded and cleaned the dataset by addressing missing values and outliers.
   - Normalized continuous features to ensure all features contribute equally to model training.
   - Handled class imbalance in the dataset using techniques like oversampling.

2. **Feature Engineering**:
   - Analyzed and engineered new features that enhance model performance.
   - Applied feature importance techniques to rank the most influential factors in hypothyroidism prediction.

3. **Model Training & Evaluation**:
   - Multiple classification models were trained and tested.
   - The best-performing model was selected based on accuracy and other evaluation metrics.

4. **Visualization**:
   - Used libraries like Matplotlib and Seaborn to visualize data distributions, feature importance, and confusion matrices.

## 📊 Results and Insights

- **Feature Importance**: TSH and T3 hormone levels were found to be the most critical features in predicting hypothyroidism.
- **Best Model**: The Random Forest model achieved the highest accuracy of **92%**, outperforming other models.
- **Model Evaluation**: Models were evaluated using precision, recall, F1-score, and ROC curves, with the Random Forest and Logistic Regression performing best.

## 🛠️ Technologies Used

- Python
- Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
