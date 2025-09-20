# Loan Approval Prediction

This project predicts loan approval using machine learning algorithms. The goal is to classify whether a loan will be approved or not based on applicant information.

---

## 📊 Algorithms Used
The project implements three machine learning algorithms:

1. **Decision Tree**
   - Recall: **1.0** → catches all positive cases (approved loans).  
   - Accuracy: **0.62 (test)** → misclassifies many negatives.  
   - Observations: Model looks overfitted (memorizes training data but generalizes poorly).

2. **Logistic Regression**
   - Accuracy: ~**0.76**  
   - Recall: ~**0.95**  
   - Observations: Performs better than Decision Tree; suitable for balanced performance between recall and accuracy.

3. **Random Forest**
   - Accuracy: ~**0.76**  
   - Recall: ~**0.95**  
   - Observations: Similar results to Logistic Regression; ensemble method improves stability.

---

## 🔧 Dataset
The dataset contains information about loan applicants with the following columns:

| Column Name           | Description |
|-----------------------|-------------|
| Loan_ID               | Unique loan identifier |
| Gender                | Male / Female |
| Married               | Applicant married or not |
| Dependents            | Number of dependents |
| Education             | Applicant education level |
| Self_Employed         | Self-employed or not |
| ApplicantIncome       | Income of the applicant |
| CoapplicantIncome     | Income of coapplicant |
| LoanAmount            | Loan amount requested |
| Loan_Amount_Term      | Loan repayment term (in months) |
| Credit_History        | Credit history (1: meets guidelines, 0: does not meet) |
| Property_Area         | Urban / Semiurban / Rural |
| Loan_Status           | Loan approval status (Y / N) |

---

## ⚙️ Steps in the Project
1. Exploratory Data Analysis (EDA)  
2. Handling missing values and outliers  
3. Feature encoding (One-Hot Encoding for categorical variables)  
4. Model training and evaluation using Logistic Regression, Decision Tree, and Random Forest  
5. Model comparison based on Accuracy and Recall  

---

## 📈 Observations
- Decision Tree has perfect recall but low accuracy → prone to overfitting.  
- Logistic Regression and Random Forest provide a better balance between accuracy and recall.  
- The dataset size and class balance affect model performance.  

---

## 📌 Conclusion
Logistic Regression and Random Forest are better choices for predicting loan approval in this dataset, providing good accuracy while maintaining high recall.

---

## 💻 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 📁 Repository Structure
