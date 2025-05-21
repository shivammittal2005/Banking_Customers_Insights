# 💼 Banking Customer Insights – EDA + Power BI Dashboard

> 📊 An end-to-end Exploratory Data Analysis (EDA) project on a banking dataset, culminating in a compelling **Power BI dashboard** to visualize customer trends, financial behavior, and risk profiles.

---

## 📂 Project Overview

This project aims to uncover key insights from banking customer data using Python-based EDA techniques and present them interactively through a Power BI dashboard.

**Key Objectives:**
- Understand customer demographics and financial patterns.
- Analyze risk behavior, account usage, and loyalty trends.
- Present findings visually for decision-making purposes.

---

## 📁 Dataset Description

The project uses multiple interlinked CSV datasets:

- `Banking.csv` – Core dataset with account and demographic data
- `Banking-Relationships.csv` – Relationship classifications
- `Investment-Advisors.csv` – Financial advisor mapping
- `Gender.csv` – Gender ID and labels

### Key Features:
- Customer Demographics (Age Band, Gender, Occupation, Nationality)
- Financial Holdings (Checking, Savings, Investment Balances)
- Risk & Loyalty Metrics (Risk Weighting, Loyalty Classification)
- Credit Card & Fee Structures

---

## 🔍 EDA Breakdown (Python + Jupyter)

### 📌 1. Univariate Analysis
- Distribution plots for demographics and financial categories
- Frequency visualizations for occupation, gender, etc.

### 📌 2. Bivariate & Comparative Analysis
- Insights on how **Income Band** impacts **Risk Weighting**
- Loyalty segmentation vs. fee structures

### 📌 3. Numerical Insights
- Correlation heatmaps revealing relationships between account types
- Use of `.describe()`, `.corr()` and pairwise visual comparisons

### 📌 4. Key Insights Extracted
- Customers with high loyalty classification often have diversified accounts.
- Income band and age are strong indicators of credit card ownership.
- Checking and savings balances show strong interdependence.

---

## 📊 Power BI Dashboard

An interactive dashboard (`Banking Analysis Dashoard.pbit`) was created using **Power BI Desktop** for:
- Visual storytelling of the EDA insights
- Filtering by demographics and account types
- Dynamic visuals: clustered bars, pie charts, maps, and KPIs

> ⚡ _Dashboard can be opened using Power BI Desktop for full interactivity._

---

## 🛠 Tools & Technologies
- MS Excel (Power Query Editor)
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Canva 
- Power BI Desktop

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/shivammittal2005/Banking_Customers_Insights.git
cd Banking_Customers_Insights
```

### Step 2: Set Up Python Environment
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Launch the Notebook
```bash
jupyter notebook EDA.ipynb
```

### Step 4: Open the Dashboard
Open `Banking Analysis Dashoard.pbit` in Power BI Desktop.

---

## ✅ Final Deliverables

- 🧠 Insight-rich Jupyter Notebook (EDA)
- 📈 Interactive Power BI Dashboard
- 📦 Multiple data files with joined and enriched data

---

## Screenshot/ Demo
![]()
