# 🧠 Loan Approval Prediction System 

### 📘 Overview
This project aims to predict whether a loan application will be **approved or rejected** based on various applicant details such as **income, education, credit history, and property area**.  

## 🧩 Project Structure

| Phase | Description |
|:------|:-------------|
| **Data Ingestion** | Load and validate the dataset, check for missing values and basic structure. |
| **Data Preprocessing** | Handle missing values, encode categorical variables, and scale numerical features. |
| **Exploratory Data Analysis (EDA)** | Visualize data distributions, correlations, and uncover key patterns affecting loan approval. |
| **Model Building & Evaluation** | Train and evaluate multiple machine learning models (Logistic Regression, Decision Tree, Random Forest). |
| **Model Comparison & Conclusion** | Compare model performance metrics and finalize the most effective predictive model. |

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries & Tools:**
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## 📊 Dataset Information
The dataset contains applicant information such as:
- Gender, Marital Status, Dependents  
- Education, Employment Type  
- Applicant & Coapplicant Income  
- Loan Amount & Loan Term  
- Credit History  
- Property Area  
- Loan Status (Target Variable)

📁 *File Name:* `loan_data.csv`  
📈 *Rows:* 614  
📊 *Columns:* 13  

---

## 🧮 Models Implemented

| Model | Accuracy | Key Highlights |
|:------|:----------|:----------------|
| **Logistic Regression** | **86.18%** | Best performing and most interpretable model. |
| Decision Tree | 76.42% | Slight overfitting observed. |
| Random Forest | 82.93% | Balanced performance, but slightly behind Logistic Regression. |

---

## 🧠 Key Insights from EDA
- Applicants with **Credit_History = 1** have a much higher approval chance.  
- **Graduates** and those from **Semiurban areas** show better approval rates.  
- **Applicant Income** alone doesn’t strongly influence approval; **Credit History** does.  
- The dataset is slightly imbalanced but manageable.

---

## 🏁 Conclusion
> **Logistic Regression** proved to be the most efficient and interpretable model with an accuracy of **~86%**, making it ideal for automating **loan eligibility screening**.  
>  
> This project demonstrates the practical application of **Machine Learning in financial decision-making**, offering an intelligent, data-driven solution for banks and credit institutions.
