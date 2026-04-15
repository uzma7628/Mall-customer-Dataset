# Mall-customer-Dataset
 *Mall Customer Dataset Description* This dataset contains basic information about mall customers such as Customer ID, Gender, Age, Annual Income, and Spending Score. It is commonly used for customer segmentation and data analysis to identify different types of customers and improve marketing strategies.
# Bank Marketing Term Deposit Prediction 🏦

This project predicts whether a customer will subscribe to a **Term Deposit** based on a marketing campaign's data. It uses Machine Learning classification and **Explainable AI (XAI)** to understand the decision-making process.

##  Objective
The goal is to build a predictive model for a Portuguese banking institution to increase the efficiency of their marketing campaigns by identifying potential customers.

## Dataset
The **Bank Marketing Dataset** from the UCI Machine Learning Repository is used. It includes:
- **Customer info:** Age, Job, Marital Status, Education, Balance.
- **Campaign info:** Contact type, Duration, Day, Month.
- **Previous outcomes:** Poutcome, Pdays.

##  Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `Pandas` & `NumPy` (Data Manipulation)
  - `Scikit-learn` (Machine Learning)
  - `SHAP` (Model Interpretability / XAI)
  - `Matplotlib` & `Seaborn` (Visualization)

## Workflow
1. **Exploratory Data Analysis (EDA):** Understanding customer distribution.
2. **Data Preprocessing:** - Handling missing values.
   - **One-Hot Encoding** for categorical features.
   - Data splitting (80% Train, 20% Test).
3. **Modeling:** - Trained a **Random Forest Classifier**.
   - Evaluated using Confusion Matrix, F1-Score, and ROC-AUC.
4. **Interpretability (XAI):** - Used **SHAP** values to explain why specific customers were predicted to subscribe or not.

## Key Results
- **Model Performance:** (Yahan apni accuracy likhein, e.g., 90%)
- **Top Predictors:** The most influential features were `duration` (call length) and `poutcome` (previous success).

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install pandas scikit-learn shap`.
3. Run the Jupyter Notebook or Python script.

---
Developed by [Aapka Naam] 🚀
