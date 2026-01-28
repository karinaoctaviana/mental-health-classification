# Mental Health Classification

This project focuses on classifying mental health conditions using machine learning techniques.  
The goal is to build a classification model that can predict mental health categories based on the given dataset and evaluate its performance using appropriate metrics.

## 📌 Project Overview
Mental health issues are increasingly recognized as an important public health concern.  
This project applies supervised machine learning to classify mental health-related data and analyze model performance, especially in the presence of class imbalance.

## 📊 Dataset
- The dataset contains features related to mental health indicators.
- Target labels represent different mental health classes.
- The class distribution shows **slight imbalance**, which influences the choice of evaluation metrics.

## ⚙️ Methodology
The main steps in this project include:
1. Data loading and exploration
2. Data preprocessing (handling missing values, encoding, normalization if needed)
3. Train–test split
4. Model training using machine learning algorithms
5. Model evaluation using suitable performance metrics

## 📈 Evaluation Metrics
Due to mild class imbalance in the dataset:
- **Weighted F1-score** is used as the primary evaluation metric  
- Accuracy is reported but not relied upon as the sole indicator of model performance

This ensures a more representative assessment of the classifier across all classes.

## 🧠 Models Used
- Machine learning classification model(s) implemented in Python  
- Libraries commonly used include:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib` / `seaborn` (for visualization)

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/karinaoctaviana/mental-health-classification.git
