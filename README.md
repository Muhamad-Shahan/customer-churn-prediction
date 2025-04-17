# Customer Churn Prediction

## 📌 Project Overview
This project aims to predict whether a customer will churn (leave a service) using historical customer data. Understanding and predicting churn is essential for businesses to implement retention strategies and improve customer satisfaction. Machine learning classification algorithms are used to identify patterns and build a predictive model.

---

## 📊 Dataset Overview
The dataset contains customer attributes such as:

- `CustomerID`: Unique customer identifier
- `Gender`: Male or Female
- `SeniorCitizen`: Whether the customer is a senior citizen
- `Partner`, `Dependents`: Demographic info
- `Tenure`: Number of months the customer has stayed
- `PhoneService`, `InternetService`, `OnlineSecurity`, etc.: Services used
- `Contract`: Type of contract (Month-to-month, One year, etc.)
- `MonthlyCharges`, `TotalCharges`: Billing information
- `Churn`: Target variable (Yes/No)

---

## 🛠️ Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Logistic Regression, Decision Tree, Random Forest, XGBoost  

---

## 🔍 Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Visualize class imbalance  
   - Identify correlations and key churn indicators

2. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Feature scaling

3. **Model Training**  
   - Split data into training and test sets  
   - Train multiple classification models  
   - Compare performance metrics

4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix  
   - ROC-AUC Curve

5. **Insights & Visualization**  
   - Feature importance analysis  
   - Customer segments with high churn risk

