# 📊 Customer Churn Prediction

This project predicts **customer churn** using machine learning techniques like **Logistic Regression and Random Forest**. It includes **exploratory data analysis (EDA), feature engineering, and model evaluation**.

## 📂 Dataset
- The dataset comes from a **telecom company** and contains **customer details, services, and churn status**.
- 📄 `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## 🔍 Project Steps
1. **Data Cleaning & Preprocessing**
   - Handled missing values (`TotalCharges`)
   - Converted categorical features using **One-Hot Encoding & Binary Encoding**
   - Scaled numerical features using **Standardization**
   
2. **Exploratory Data Analysis (EDA)**
   - Analyzed **customer behavior, contract types, and payment methods** affecting churn
   - Visualized churn impact using **Seaborn & Matplotlib**
   
3. **Machine Learning Models**
   - **Logistic Regression** (Baseline Model)
   - **Random Forest Classifier** (Best Performing Model)
   - **Adjusted Decision Threshold** to improve recall
   
4. **Model Evaluation**
   - **Accuracy, Precision, Recall, F1-score**
   - **Random Forest outperformed Logistic Regression**

## 🛠️ Technologies Used
- Python 🐍
- Pandas, NumPy (Data Processing)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-Learn (Machine Learning)

## 🚀 How to Run the Project
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Customer-Churn-Prediction.git
