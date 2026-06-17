# 💰 SmartLoan - AI Powered Loan Approval Prediction System

An end-to-end Machine Learning project that predicts loan approval status based on applicant information using data preprocessing, feature engineering, and classification algorithms.

This project demonstrates the complete ML workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, encoding, feature scaling, model training, evaluation, and prediction.

---

## 🚀 Project Overview

Financial institutions receive thousands of loan applications every day. Manual verification of applicants is time-consuming and prone to inconsistencies.

The SmartLoan system leverages Machine Learning techniques to analyze applicant details and predict whether a loan application is likely to be approved or rejected.

The project focuses on:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Categorical Encoding
- Feature Scaling
- Machine Learning Model Development
- Model Evaluation and Comparison

---

## 📊 Dataset Information

The dataset contains applicant information such as:

| Feature | Description |
|----------|-------------|
| Gender | Applicant Gender |
| Married | Marital Status |
| Dependents | Number of Dependents |
| Education | Education Level |
| Self_Employed | Employment Status |
| ApplicantIncome | Applicant Income |
| CoapplicantIncome | Co-applicant Income |
| LoanAmount | Requested Loan Amount |
| Loan_Amount_Term | Loan Duration |
| Credit_History | Credit History Score |
| Property_Area | Urban/Semiurban/Rural |
| Loan_Status | Target Variable |

---

## 🛠️ Machine Learning Workflow

### 1️⃣ Data Preprocessing

- Handled missing values
- Removed inconsistencies
- Checked data types
- Prepared data for modeling

### 2️⃣ Exploratory Data Analysis (EDA)

Performed:

- Distribution Analysis
- Correlation Analysis
- Univariate Analysis
- Bivariate Analysis
- Feature Relationships

### 3️⃣ Feature Engineering

- Label Encoding
- One-Hot Encoding
- Feature Selection
- Data Transformation

### 4️⃣ Feature Scaling

Applied:

- StandardScaler

to normalize numerical features before model training.

---

## 🤖 Models Implemented

### Logistic Regression

A baseline classification model used for loan approval prediction.

### K-Nearest Neighbors (KNN)

A distance-based classification algorithm used for comparative analysis.

### Naive Bayes

A probabilistic machine learning algorithm suitable for classification tasks.

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross Validation

### Performance Highlights

✅ Achieved **85%+ prediction accuracy**

✅ Compared multiple classification models

✅ Selected the best-performing model based on evaluation metrics

---

## 📂 Project Structure

```text
SmartLoan-AI-Powered-Loan-Approval-Prediction-System/
│
├── credit_wise.ipynb
├── loan_approval_data.csv
├── README.md
│
└── Outputs/
    ├── EDA Visualizations
    ├── Correlation Heatmaps
    └── Model Evaluation Results
```

---

## 🧰 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning

- Logistic Regression
- KNN
- Naive Bayes

### Development Environment

- Jupyter Notebook

---

## 📊 Key Insights

- Credit History is one of the strongest indicators of loan approval.
- Applicant Income significantly impacts loan eligibility.
- Proper feature scaling improves model performance.
- Classification algorithms can effectively automate loan approval prediction.

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/ABHISHEK-MARIGERI/SmartLoan-AI-Powered-Loan-Approval-Prediction-System.git
```

### Navigate to Project

```bash
cd SmartLoan-AI-Powered-Loan-Approval-Prediction-System
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
credit_wise.ipynb
```

and run all cells.

---

## 🎯 Business Impact

This system can help financial institutions:

- Reduce manual loan screening efforts
- Improve decision-making efficiency
- Identify high-risk applications
- Support data-driven lending strategies

---

## 📌 Future Enhancements

- Hyperparameter Optimization
- Random Forest Classifier
- XGBoost Implementation
- Loan Approval Web Application
- Model Deployment using Streamlit
- Real-Time Prediction API

---

## 👨‍💻 Author

**Abhishek Marigeri**


---

## ⭐ If you found this project useful

Please consider giving this repository a **Star ⭐**.
