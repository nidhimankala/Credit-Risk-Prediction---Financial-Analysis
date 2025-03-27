# 🎯 Credit Risk Analysis & Prediction 🚀  

## 📌 Overview  
This project analyzes financial factors influencing **loan approvals** and builds a predictive model to assess borrower risk. Using **machine learning**, we classify applicants based on their likelihood of meeting **credit policy**.  

## 📊 Dataset  
The dataset includes:  
- 🏦 **credit.policy** – Whether a borrower meets lending criteria.  
- 📈 **fico** – Borrower’s **FICO credit score** (key indicator of creditworthiness).  
- 💰 **int.rate** – Loan **interest rate** (higher rates indicate higher risk).  
- 🔄 **dti** – **Debt-to-income ratio**, showing financial health.  
- 💳 **revol.bal** – Revolving balance of the borrower.  
- 🎯 **purpose** – The reason for the loan (e.g., **credit card, debt consolidation**).  

## 🔍 Approach  
1️⃣ **Exploratory Data Analysis** – Identified key trends & imbalances.  
2️⃣ **Preprocessing** – Handled missing data, encoded categorical variables, and balanced the dataset using **SMOTE**.  
3️⃣ **Modeling** – Tested **Logistic Regression and Random Forest**.  
4️⃣ **Evaluation** – **Random Forest** performed best with **97% accuracy**!  
5️⃣ **Key Insights**:  
   - 📌 **FICO score** and **credit history** are strong indicators of loan approval.  
   - ⚠️ **Higher interest rates** are correlated with riskier borrowers.  
   - 🏡 **Loan purpose** significantly impacts approval chances.  

## 📈 Business Recommendations  
✅ **Strengthen credit policy** using key predictors like **FICO score & DTI ratio**.  
✅ **Adjust interest rates** based on borrower risk profiles.  
✅ **Introduce targeted loan products** for specific borrower segments.  

## ⚙️ Requirements  
- 🐍 Python 3.x  
- 📦 Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

## 🚀 Usage  
1️⃣ Install dependencies:  
   ```bash
   pip install -r requirements.txt
