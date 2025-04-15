# Telco Customer Churn Prediction 📉📞

This machine learning project aims to predict customer churn in a telecommunications company. The workflow includes an Exploratory Data Analysis (EDA) and the implementation of classification models to identify relevant patterns in customer behavior.

## 🧠 Objective

The goal is to predict whether a customer will cancel their service based on features such as contract type, internet usage, payment methods, and more. These insights can help design strategies to improve customer retention.

## 📊 Dataset

The dataset used is the **Telco Customer Churn** dataset from IBM, which contains demographic data, service usage, and billing information for each customer.

- **Size:** ~7,000 entries  
- **Key features:** `gender`, `SeniorCitizen`, `Partner`, `tenure`, `Contract`, `MonthlyCharges`, `Churn`  
- **Target variable:** `Churn` (Yes/No)

## 🔍 Workflow

1. **Data Loading & Cleaning**  
   - Missing value handling  
   - Categorical data conversion

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of variables  
   - Relationships between features and `Churn`  
   - Visualizations using `seaborn`, `matplotlib`, and `pandas`

3. **Preprocessing**  
   - One-hot encoding  
   - Feature scaling for continuous variables

4. **Modeling**  
   - Training classification models (`Random Forest`, `MLP Neural Network`, etc.)  
   - Evaluating using metrics: *Accuracy*, *Precision*, *Recall*, *F1-score*, *ROC-AUC*

5. **Interpretation**  
   - Feature importance  
   - Confusion matrix and ROC curves

## 🛠️ Technologies

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  
- Jupyter Notebook

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/arielpincayy/Telco_Churn.git
cd Telco_Churn
