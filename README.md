

# 📊 Telecom Service Churn Prediction

### 🔍 A Machine Learning Approach to Predict Customer Churn in the Telecom Sector

---

## 📌 Project Overview

This project aims to **predict customer churn** using various machine learning models to help telecom providers proactively retain their customers. Based on real-world data and methodologies from published research, we evaluated model performance and enhanced churn prediction with advanced techniques.

---

## 👥 Team Members

- **Chittesh S** - CB.EN.U4ECE23212  
- **CH. Saathvik** - CB.EN.U4ECE23214  
- **M. Rahul** - CB.EN.U4ECE23227  

---

## 🎯 Objectives

- Predict customer churn using models like Decision Trees, Random Forest, SVM, KNN, Naive Bayes, SGD, and ADAM.
- Address class imbalance using **SMOTE**.
- Perform **Survival Analysis** to estimate customer lifetime.
- Evaluate models using metrics: Accuracy, Precision, Recall, F1-Score.
- Identify key features influencing churn for better decision-making.

---

## 📁 Dataset

- **Source**: [Telco Customer Churn Dataset - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- Contains customer demographics, account info, and service usage.

---

## 🛠️ Models Used

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Stochastic Gradient Descent (SGD)
- Multi-layer Perceptron (MLP) with ADAM Optimizer

---

## ⚖️ Techniques Applied

- **Data Preprocessing**: Feature engineering, one-hot encoding
- **Class Balancing**: SMOTE
- **Model Optimization**: ADAM & SGD
- **Evaluation**: Confusion Matrix, ROC, Survival Plots

---

## 🏆 Key Results

- **Random Forest** achieved ~98% accuracy and strong precision/recall.
- SMOTE significantly improved model fairness across classes.
- Survival analysis (Kaplan-Meier) helped estimate customer retention trends.

---

## 📈 Performance Metrics

| Model           | Accuracy | Precision | Recall | F1-Score |
|----------------|----------|-----------|--------|----------|
| Random Forest  | 98%      | 97.88%    | 96.71% | 97.29%   |
| Decision Tree  | Comparable with base paper |
| Others         | Used for benchmarking and additional insights |

---

## 📆 Timeline

- **Week 1–2**: Literature Review and Base Paper Analysis  
- **Week 3–4**: Dataset preprocessing & Exploration  
- **Week 5–6**: Model Development & Base Paper Implementation  
- **Week 7–8**: Optimization, Testing, and Final Evaluation  

---

## 📚 References

1. Sharmila K. Wagh et al., *Customer churn prediction in telecom sector using machine learning techniques*, Results in Control and Optimization, 2024.
2. Abhishek Gaur, Ratnesh Dubey, *IEEE Conference 2018*, DOI: 978-1-5386-5367-8/18.
3. [Telco Customer Churn Dataset - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
4. [Lifelines - Survival Analysis in Python](https://lifelines.readthedocs.io/en/latest/)

---


## ✅ Conclusion

This project showcases the application of machine learning to real-world problems like customer churn in telecom. Using ensemble methods and data balancing techniques, we built a robust and reliable churn prediction model with actionable business insights.

