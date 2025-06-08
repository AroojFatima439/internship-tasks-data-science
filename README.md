# 🧠 Data Science & Analytics Internship Tasks

This repository contains completed tasks from my **Data Science & Analytics Internship** at **DevelopersHub Corporation**. Each task demonstrates key skills in data preprocessing, visualization, machine learning modeling, and evaluation.

---

## ✅ Task 1: Exploring and Visualizing the Iris Dataset

### 🎯 Objective
Explore the Iris dataset to understand feature distributions and relationships.

### 🛠️ Approach
- Loaded dataset using `pandas` and `seaborn`.
- Performed structural inspection using `.shape`, `.columns`, and `.head()`.
- Visualized feature relationships using:
  - Scatter plots
  - Histograms
  - Box plots

### 🔧 Tools Used
`Pandas`, `Seaborn`, `Matplotlib`

### 📊 Insights
- Petal features show clear separability by species.
- Sepal width has noticeable outliers in the `setosa` class.

---

## 🧾 Task 2: Credit Risk Prediction - Loan Default Classification

### 🎯 Objective
Predict whether a loan applicant is likely to default on a loan using personal, financial, and credit-related attributes.

### 🛠️ Approach
1. **Data Preprocessing**
   - Handled missing values:
     - Categorical: Filled with mode
     - Numerical: Filled with median
2. **EDA**
   - Visualized:
     - Loan Amount distribution
     - Loan Status across Education
     - Applicant Income vs Loan Status
3. **Feature Engineering**
   - One-hot encoded categorical variables
   - Mapped `Loan_Status`:
     - `'Y' → 1`, `'N' → 0`
4. **Model Training**
   - Logistic Regression (train-test split 80/20)
5. **Evaluation**
   - Accuracy Score: `78.86%`
   - Confusion Matrix

### 📈 Key Insights
- Higher income and good credit history improve approval chances.
- Education level and loan amount moderately impact decisions.

### 📁 Dataset Columns
| Column             | Description                       |
|--------------------|-----------------------------------|
| Loan_ID            | Unique Loan ID                    |
| Gender             | Male / Female                     |
| Married            | Marital Status                    |
| Dependents         | Number of dependents              |
| Education          | Graduate / Not Graduate           |
| Self_Employed      | Employment status                 |
| ApplicantIncome    | Monthly income of applicant       |
| CoapplicantIncome  | Monthly income of co-applicant    |
| LoanAmount         | Loan amount requested             |
| Loan_Amount_Term   | Term of loan in months            |
| Credit_History     | 1 = Good credit, 0 = Bad credit   |
| Property_Area      | Urban / Rural / Semiurban         |
| Loan_Status        | Target variable (Y/N)             |

### 🔧 Tools Used
`Pandas`, `Seaborn`, `Matplotlib`, `Scikit-learn`

### 🚀 Future Improvements
- Try Decision Tree, Random Forest, XGBoost
- Use cross-validation
- Add feature importance ranking

---

## 📦 Task 3: Customer Churn Prediction (Bank Customers)

### 🎯 Objective
Identify customers likely to leave the bank based on behavior and account features.

### 🛠️ Approach
- Cleaned and encoded categorical features: `Geography`, `Gender`
- Trained a **Random Forest Classifier**
- Analyzed **feature importance**

### ✅ Results
- **Model Accuracy**: `86%`
- Performs well for non-churners (Class 0)
- Moderate recall for churners (Class 1)

### 📊 Key Insights
- **Top Influential Features**:
  - Age, Balance, NumOfProducts, IsActiveMember, Geography
- Suggest using **SMOTE**, **XGBoost**, or **hyperparameter tuning** for better churn recall

### 🔧 Tools Used
- Python (`Pandas`, `NumPy`, `Scikit-learn`)
- Visuals: `Seaborn`, `Matplotlib`
- Classifier: `RandomForestClassifier`

### 📁 Dataset
- **Churn Modelling Dataset**
- Shape: `(10000, 14)`
- No missing values

### 🧠 Conclusion
Successfully predicted churn using a balanced model, showing strong potential in financial churn prevention.

---

## 📎 Repository Structure


