# 📊 Telco Customer Churn Analysis / Análise de Churn de Clientes de Telecomunicações

## 🇺🇸 Project Overview
Exploratory Data Analysis (EDA) focused on understanding customer churn behavior in a telecommunications company.  
The goal is to identify which factors most influence cancellations and extract actionable insights for customer retention.

**Main steps:**
- Data cleaning and preprocessing  
- Descriptive statistics and exploratory analysis  
- Visualizations of key relationships (contract, payment, tenure, internet type)  
- Correlation analysis and insights summary  

**Tools used:**  
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook  

---

## 🇧🇷 Visão Geral do Projeto
Análise Exploratória de Dados (EDA) voltada para entender o comportamento de cancelamento de clientes em uma empresa de telecomunicações.  
O objetivo é identificar os fatores que mais influenciam o churn e gerar insights para estratégias de retenção.

**Etapas principais:**
- Limpeza e preparação dos dados  
- Estatísticas descritivas e análise exploratória  
- Visualizações das principais relações (contrato, pagamento, tempo de permanência, tipo de internet)  
- Análise de correlação e resumo de insights  

**Ferramentas utilizadas:**  
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook  

---

## 📁 Dataset
The dataset used is the **Telco Customer Churn** dataset, which contains 7,043 customer records and 21 columns.  
It includes demographic data, service information, contract type, payment methods, and a churn indicator (Yes/No).

| Column | Description |
|--------|--------------|
| `customerID` | Unique customer identifier |
| `tenure` | Months as a customer |
| `Contract` | Contract type (Month-to-month, One year, Two year) |
| `PaymentMethod` | Payment method |
| `InternetService` | Type of internet service |
| `MonthlyCharges` | Monthly fee |
| `TotalCharges` | Total amount paid |
| `Churn` | Target variable – customer churn (Yes/No) |

---

## 📈 Key Insights
- Customers with **month-to-month contracts** have the highest churn rate.  
- **Electronic check** users show a higher probability of churn.  
- Customers with **fiber optic internet** tend to leave more often.  
- **Shorter tenure** (newer customers) strongly correlates with churn.  

---

## 🧠 Conclusions
The analysis highlights that **contract duration, payment type, and customer loyalty time** are the most relevant factors influencing churn.  
Potential business actions:
- Offer incentives for long-term contracts.  
- Investigate dissatisfaction among fiber optic users.  
- Develop onboarding or loyalty programs for new clients.  

---

## 🚀 How to Run
1. Clone this repository  
2. Open the `.ipynb` notebook file in Jupyter or VS Code  
3. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn
