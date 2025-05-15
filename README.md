# 🧠 Breast Cancer Prediction using Logistic Regression

This project aims to predict whether a tumor is **malignant** or **benign** using the Breast Cancer Wisconsin dataset. Leveraging logistic regression, the model supports early diagnosis through pattern recognition in medical imaging data.

## 🖼️ Visual Context

### 1. Tumor Detection in Breast Imaging  
![41598_2024_57740_Fig1_HTML](https://github.com/user-attachments/assets/c1ff0318-b877-40e7-a72c-4bde799c8f7b)


### 2. Benign vs Malignant Tumor Structure  
![download](https://github.com/user-attachments/assets/5a4c2091-409d-4576-ac12-d3ce6f59ca3b)


## 📌 Project Overview

Breast cancer is one of the most common cancers globally, and early diagnosis plays a crucial role in improving survival rates. In this project, we:

- Analyzed the dataset with 569 records and 30 features extracted from digitized images of breast mass.
- Built a logistic regression model to classify tumors as **malignant (M)** or **benign (B)**.
- Evaluated model performance using multiple classification metrics.

## 📁 Dataset

- **Source:** [Kaggle - Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Records:** 569
- **Features:** 30 numeric features + Diagnosis (Target: M/B)

## ⚙️ Technologies Used

- **Python** (Jupyter Notebook)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 📊 Key Steps

1. **Data Preprocessing**
   - Removed irrelevant columns (`id`, `Unnamed: 32`)
   - Encoded target labels (`M` = 1, `B` = 0)
   - Scaled numeric features for better model performance

2. **Exploratory Data Analysis**
   - Distribution plots of key features
   - Heatmap for correlation analysis
   - Diagnosis count visualization

3. **Model Building**
   - Applied logistic regression from scikit-learn
   - Split data into training and test sets (80/20)

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix and ROC-AUC curve

## 📈 Results

- Achieved **>98% accuracy**
- Strong precision and recall, demonstrating effective classification capability
- Clear and interpretable performance using logistic regression


