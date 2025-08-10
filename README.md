# Telecom-Customer-Churn-prediction-

# 📞 Telecom Customer Churn - Exploratory Data Analysis

This project focuses on **exploratory data analysis (EDA)** of telecom customer data to understand churn patterns.  
The aim is to discover trends, correlations, and key factors that influence whether customers stay or leave.

---

## 📌 Overview
Customer churn occurs when customers discontinue their subscription.  
By exploring the dataset, we can:
- Identify churn rates and patterns.
- Understand the profile of customers more likely to churn.
- Highlight potential business actions to reduce churn.

---

## 📂 Dataset
**File:** `Telecom-Customer-Churn-prediction.xlsx` (and cleaned CSV version)  
**Rows:** ~7,000 customers  
**Columns:**
- **Demographics:** Gender, Senior Citizen, Partner, Dependents
- **Services:** Phone Service, Multiple Lines, Internet Type, Online Security, Backup, Device Protection, Tech Support, Streaming TV/Movies
- **Account Info:** Tenure, Contract Type, Payment Method, Paperless Billing, Monthly Charges, Total Charges
- **Target:** `Churn` (Yes/No)

---

## 🔍 Exploratory Data Analysis
**Steps performed:**
1. **Data Cleaning**  
   - Removed duplicates  
   - Fixed inconsistent values  
   - Handled missing data  
   - Standardized categorical values
2. **Univariate Analysis**  
   - Count plots for categorical variables  
   - Histograms for numerical variables
3. **Bivariate Analysis**  
   - Churn vs. Contract Type, Payment Method, Internet Service  
   - Relationship between tenure and churn  
   - Churn trends by Online Security, Tech Support
4. **Key Insights:**
   - Churn Rate: ~26.6%  
   - Month-to-month contracts have the highest churn (~75%)  
   - Electronic Check payment customers churn more  
   - Fiber optic users churn more than DSL users  
   - Customers without online security or tech support churn more  
   - Shorter tenure = higher churn

---

## 📊 Visualizations
- Bar plots for categorical features vs churn  
- Histogram and KDE plots for numeric features  
- Heatmap for correlation between numeric variables

---

## ⚙️ Installation & Usage
1. Clone this repository: https://github.com/SPOORTHI-HR/Telecom-Customer-Churn-prediction-

2. Install dependencies:
pip install -r requirements.txt

Open the Jupyter notebook:
jupyter notebook

Run Telecom-Customer-Churn-prediction.ipynb to reproduce the analysis.

📜 License
This project is licensed under the MIT License.
   git clone https://github.com/SPOORTHI-HR/Telecom-Customer-Churn-prediction-.git
   cd Telecom-Customer-Churn-prediction-
