# 🍚 Rice Variety Classification – Machine Learning Models

A supervised machine-learning project designed to classify rice varieties using multiple algorithms, evaluate performance, and analyze the effect of preprocessing techniques such as normalization.  
This repository includes the **dataset** and a **single Python script** containing all model implementations.

---

## 📌 Project Overview

This project builds and compares several ML models to classify rice grains based on numerical features extracted from the dataset. The work includes:

- Data preprocessing  
- Exploratory analysis  
- Normalization (Standardization)  
- Model training  
- Performance comparison  
- Visualization of decision boundaries and evaluation metrics  

The goal is to determine which ML algorithm performs best for the rice classification task.

---

## 🧪 Machine Learning Models Used

The following algorithms were implemented and evaluated:

- **Support Vector Machine (SVM)**  
- **Artificial Neural Network (ANN / MLPClassifier)**  
- **Logistic Regression**  
- **Naive Bayes**  
- **Random Forest**

📌 **Best Model:**  
**SVM achieved the highest accuracy: 0.99**, outperforming all other algorithms.

---

## 📊 Key Insights & Learning Outcome

- Normalizing the data using **StandardScaler** significantly improved model performance.
- SVM showed superior classification capability on this dataset.
- ANN and Random Forest also performed strongly, but slightly below SVM.
- Naive Bayes struggled due to strong assumptions about feature distribution.

---
📂 rice-classification/
│──  rice_classification.py # Contains all ML algorithms
│──  rice_dataset.csv # Full dataset
│──  requirements.txt # Dependencies
│──  README.md # Project documentation


---

## 📊 Model Performance Summary

After training and evaluating all models:

| Model | Accuracy |
|-------|----------|
| **SVM** | **0.99 (Best)** |
| ANN | 0.987 |
| Logistic Regression | 0.989 |
| Random Forest | 0.988 |
| Naive Bayes | 0.982 |

🔍 **SVM achieved the highest accuracy (99%)**, outperforming all other algorithms.

✨ Additionally, applying **Standardization** improved accuracy and stability across all models.

---

## 🧪 Features & Workflow

### 1️⃣ **Data Preprocessing**
- Handling missing values  
- Encoding labels  
- Feature scaling (**StandardScaler**)  
- Train/test split  

### 2️⃣ **Model Training**
Each algorithm is implemented inside the same Python script:

- `train_svm()`
- `train_ann()`
- `train_random_forest()`
- `train_logistic_regression()`
- `train_naive_bayes()`

### 3️⃣ **Evaluation**
Includes:
- Accuracy score  
- Confusion matrix  
- Classification report  
- Training visualizations  


## 📁 Repository Structure

