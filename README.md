# 📊 Financial Health Assessment Tool (Credit Risk Prediction)

## 📌 Context
In modern finance, businesses face the constant challenge of managing debt effectively while maintaining financial stability and growth. Investors and credit rating agencies rely heavily on financial statements to evaluate the **creditworthiness and risk exposure** of companies.  

This project focuses on building a **Financial Health Assessment Tool** using **machine learning techniques** to predict whether a company will default on its debt repayments in the next two quarters.

---

## 🎯 Objective
The goal is to empower businesses and investors with a robust mechanism to evaluate the financial well-being of companies. Specifically, the tool provides:

- **Debt Management Analysis**  
  Identify trends in debt management practices and detect potential default risks.

- **Credit Risk Evaluation**  
  Leverage financial indicators (liquidity ratios, debt-to-equity, etc.) to evaluate default likelihood.

---

## 📂 Project Files
- **`FRA_Main_Project_Part_A_Guided.ipynb`** → Jupyter Notebook with full data preprocessing, modeling, and evaluation workflow.  
- **`FRA_Main_Project_Part_A_Guided.pdf`** → Final report documenting methodology, findings, and recommendations.  
- **`FRA_DataDictionary.xlsx`** → Data dictionary explaining each financial metric used.  
- **`CompData1.csv`** → Dataset in csv.
---

## 🛠️ Approach
1. **Exploratory Data Analysis (EDA):**  
   - Studied distributions, correlations, and trends in financial indicators.  
   - Identified outliers and missing values impacting model performance.  

2. **Data Preprocessing:**  
   - Imputed missing values (median/mode).  
   - Treated outliers using IQR.  
   - Created engineered features (liquidity flags, leverage ratios).  
   - Normalized and scaled numerical variables.  

3. **Model Building:**  
   - Tested multiple models: Logistic Regression, Random Forest, XGBoost.  
   - Hyperparameter tuning using GridSearchCV/RandomizedSearchCV.  

4. **Model Validation:**  
   - Evaluated models using Accuracy, Precision, Recall, F1-score, and ROC-AUC.  
   - Focused on **recall** to minimize false negatives (missed defaulters).  

5. **Final Model:**  
   - Random Forest and XGBoost emerged as top-performing models with strong predictive accuracy and recall.  

---

## 📈 Results & Insights
- **Key Predictors:** Debt-to-equity ratio, liquidity ratios, and profitability metrics strongly influence default likelihood.  
- **Performance:** Best models achieved **high ROC-AUC and recall**, enabling proactive identification of default risk.  
- **Business Value:** Provides a **data-driven risk assessment framework** for credit rating agencies and investors to make informed decisions.  

---

## ✅ Recommendations
- Deploy the model in production to score companies quarterly.  
- Prioritize monitoring of firms with high leverage and poor liquidity ratios.  
- Continuously retrain the model with updated financial data to capture changing market trends.  

---

## 🚀 Tech Stack
- **Python (Pandas, NumPy, Scikit-learn, XGBoost)**  
- **Visualization:** Matplotlib, Seaborn  
- **Modeling:** Logistic Regression, Random Forest, XGBoost  
- **Validation:** Cross-validation, ROC-AUC, confusion matrices  

--- 
