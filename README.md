# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview
Customer churn is a major concern for telecom companies because losing customers directly impacts revenue and increases customer acquisition costs. This project analyzes a telecom customer dataset to identify patterns and factors that influence customer churn.

The goal of this analysis is to understand customer behavior and identify key variables that contribute to churn so that businesses can develop better retention strategies.

---

# 🎯 Problem Statement
Telecom companies often struggle to retain customers due to competitive pricing, service quality issues, and customer dissatisfaction. Identifying the factors that lead to churn can help businesses take proactive steps to reduce customer loss.

This project aims to analyze telecom customer data and answer the following questions:

- What percentage of customers are churning?
- Which customer groups are more likely to churn?
- How do services, contracts, and payment methods affect churn?
- What business strategies can reduce churn?

---

# 📂 Dataset Information
The dataset contains **7,043 customer records** with **21 features** describing customer demographics, account information, and services used.

### Key Variables

**Customer Demographics**
- Gender
- Senior Citizen

**Account Information**
- Tenure
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges

**Services Used**
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Tech Support
- Streaming TV

**Target Variable**
- `Churn` (Yes / No)

---

# 🛠 Tools & Technologies Used

- Python  
- Pandas – Data cleaning and manipulation  
- NumPy – Numerical operations  
- Matplotlib – Data visualization  
- Seaborn – Statistical visualization  
- Jupyter Notebook – Analysis environment  

---

# 🧹 Data Cleaning & Preprocessing

Several preprocessing steps were performed before analysis.

### Handling Missing Values
Some values in the **TotalCharges** column were blank for customers with **0 months tenure**. These values were replaced with **0** to maintain consistency.

### Data Type Conversion
The **TotalCharges** column was converted from object type to numeric format for analysis.

### Feature Transformation
The **SeniorCitizen** column originally had values **0 and 1**. These were converted to **"No" and "Yes"** for better readability during analysis.

---

# 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand customer distribution and identify patterns associated with churn.

Visualizations were created to analyze relationships between churn and various features such as:

- Customer tenure  
- Contract type  
- Payment method  
- Service usage  
- Customer demographics  

---

# 📈 Key Insights

## Overall Churn Rate
- **26.54% of customers have churned**
- **73.46% of customers remain with the company**

This indicates that approximately **1 in 4 customers leaves the service**.

---

## Senior Citizen Analysis
- Senior citizens show a **higher churn percentage** compared to non-senior customers.

This may indicate service usability or pricing concerns among older customers.

---

## Tenure Impact
Customer tenure strongly affects churn behavior.

- Customers with **1–2 months tenure show the highest churn rates**
- Customers with **longer tenure are less likely to churn**

This indicates that **customer retention efforts should focus on the early stages of the customer lifecycle**.

---

## Contract Type
Contract type significantly influences churn.

- **Month-to-Month contracts have the highest churn rate**
- **1-year and 2-year contracts have much lower churn rates**

Long-term contracts improve customer retention.

---

## Service Usage
Customers using more telecom services tend to stay longer.

Services associated with **lower churn** include:

- Phone Service  
- Internet Service (DSL)  
- Online Security  

Customers without services such as **Online Backup, Tech Support, or Streaming TV** show higher churn rates.

---

## Payment Method
Payment method also impacts churn.

- Customers using **Electronic Check** show the **highest churn percentage**.

Other payment methods such as automatic bank transfer or credit card payments show lower churn rates.

---

# 💡 Business Recommendations

Based on the analysis, telecom companies can reduce churn by implementing the following strategies.

### Improve Early Customer Experience
Since churn is highest during the first few months, improving onboarding and early customer support is critical.

### Encourage Long-Term Contracts
Offering discounts or incentives for **1-year or 2-year contracts** can reduce churn.

### Promote Value-Added Services
Encouraging customers to adopt services such as:

- Online Security  
- Online Backup  
- Tech Support  

can increase engagement and retention.

### Optimize Payment Options
Encouraging customers to switch from **electronic check payments to automatic payment methods** may improve retention.

---

# 📂 Project Structure

```
Telecom-Customer-Churn-Analysis
│
├── TCA.ipynb
├── Telecom_Customer_Churn_Analysis_Report.pdf
├── dataset.csv
└── README.md
```

---

# 📌 Conclusion

This project analyzed telecom customer data to identify patterns influencing churn.

Key findings include:

- **26.54% overall churn rate**
- Higher churn among **new customers**
- Highest churn in **month-to-month contracts**
- Increased churn among customers using **electronic check payments**
- Lower churn among customers using multiple telecom services

Understanding these insights allows companies to implement targeted retention strategies and improve customer satisfaction.

---

# 👨‍💻 Author

**Kshitiz**  
Aspiring Data Analyst

Skills:
- SQL  
- Python  
- Data Analysis  
- Data Visualization  
- Exploratory Data Analysis
