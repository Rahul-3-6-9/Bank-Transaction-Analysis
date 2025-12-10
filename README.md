# Unified Financial Intelligence Model (UFIM)

This project is a **single Jupyter Notebook** that performs end-to-end financial analysis on bank transaction data available [here](https://www.kaggle.com/datasets/devildyno/indian-bank-statement-one-year).  

---

# Notebook Name
`TransactionsAnalysis.ipynb`

This notebook contains:

- Data loading & cleaning  
- Rich EDA across income, expenses, patterns, and habits  
- Machine learning models for classification, anomaly detection, forecasting  
- Visualizations and financial insights  

---

# Exploratory Data Analysis (EDA)

Through this project I tried answering the given financial questions using the transaction data.

## **A. Income (Credits)**

- Count of credit transactions from “OTHERS” and their likely sources  
- Number of credit UPI transactions and frequent senders  
- Month-to-month income consistency  
- Highest-income month  
- Detection of irregular or unexpected credit spikes  

---

## **B. Expenses (Debits)**

- Number of UPI debit transactions and top recipients  
- Category breakdown (Food, Delivery, Travel, Shopping, etc.)  
- Observation that card usage is low (UPI-dominant behavior)  
- ATM withdrawals and their potential usage patterns  
- Spending categories causing overspending  

---

## **C. Cash Flow Behaviour**

- Months with negative net savings  
- Identification of unsafe low-balance days  
- Weekday vs weekend spending comparison  
- 3-month spend trend analysis  

---

## **D. Patterns & Habits**

- Top 10 most frequent UPI recipients  
- Merchants appearing repeatedly → potential subscriptions  
- Time-of-day spikes in spending  
- Week-1 vs end-of-month spending pattern  

---

# Machine Learning (ML)

The notebook includes four ML sections that automate deeper financial understanding.

---

## **1. Category Classification Model**

A TF-IDF + Logistic Regression model predicts categories (e.g., Fuel, Food, Shopping) from narration text.

Used for:
- Automated spend labeling  
- Category-level insights  
- Tracking category growth over months  

---

## **2. Anomaly Detection**

Using **Isolation Forest**, the notebook detects:

- Duplicate UPI payments  
- Unusually large debits  
- Repeated suspicious micro-charges  
- Transactions that differ from your typical behavior  

---

## **3. Spending Forecasting**

With **Facebook Prophet**, the notebook forecasts future spending:

- Predicts next-month expenditure  
- Identifies seasonal patterns  
- Detects likely future spikes or dips  

---

## **4. Behavioural Drift Analysis**

This ML section measures how your financial discipline changes over time:

- Month-to-month spend drift  
- Transaction frequency drift  
- Category drift  
- Stability score of spending behavior  

---

# Notebook Workflow

The notebook follows this structure:

1. **Load Dataset**  
2. **Clean & preprocess transactions**  
3. **Exploratory Data Analysis (EDA)**  
4. **Feature engineering**  
5. **Category classification model**  
6. **Anomaly detection model**  
7. **Forecasting model**  
8. **Behavior drift analysis**  
9. **Financial insights & recommendations**  


---
