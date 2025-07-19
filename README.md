# 📊 Advertising Click Prediction Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

---

## **📌 Overview**
This project uses a **synthetic advertising dataset** to predict whether an internet user will **click on an advertisement** based on their demographic and behavioral features. The objective is to develop and evaluate a **machine learning model** for this classification problem.

---

## **📂 Dataset Information**
The dataset includes the following features:

- **Daily Time Spent on Site**: Consumer time on site (in minutes)  
- **Age**: Customer age (in years)  
- **Area Income**: Average income of the consumer's geographical area  
- **Daily Internet Usage**: Average minutes per day the consumer spends online  
- **Ad Topic Line**: Headline of the advertisement  
- **City**: City of the consumer  
- **Male**: Whether the consumer is male (binary)  
- **Country**: Country of the consumer  
- **Timestamp**: Time when the consumer clicked the ad or closed the window  
- **Clicked on Ad**: **Target variable** (0 = did not click, 1 = clicked)  

---

## **🎯 Project Objectives**
- Perform **Exploratory Data Analysis (EDA)** using Seaborn visualizations.
- Apply **data preprocessing and feature engineering**.
- Split data into **training** and **testing** sets.
- Build a **Logistic Regression model** to predict ad clicks.
- Evaluate performance using metrics like:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## **🛠️ Tools & Libraries**
- **Python 3.8+**
- **Pandas** (data manipulation)
- **NumPy** (numerical computations)
- **Matplotlib & Seaborn** (visualization)
- **Scikit-learn** (model building & evaluation)
- **Jupyter Notebook**

---

## **🔍 Workflow**
1. **Exploratory Data Analysis (EDA)**
   - Feature relationships
   - Correlation analysis
2. **Data Engineering**
   - Initial transformations (later discarded due to overfitting)
3. **Model Development**
   - Train-test split
   - Logistic Regression model
4. **Prediction & Evaluation**
   - Performance evaluation using classification metrics

---

## **📈 Results**
- Built and evaluated a Logistic Regression classifier for ad click prediction.
- Achieved good accuracy and interpretability with baseline methods.

---

## **📦 Installation & Usage**
To run this project locally:

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/Sammy-mercy/Advertising_project.git
