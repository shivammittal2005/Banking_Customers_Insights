
# 📊 Bank Customer Data EDA

This project performs **Exploratory Data Analysis (EDA)** on a banking dataset to derive meaningful insights about customer behavior, account holdings, and risk characteristics.

---

## 📁 Dataset Overview

The dataset used in this project is loaded from a CSV file named `Banking.csv`. It includes features such as:

- Customer demographics (e.g., Gender, Nationality, Income Band)
- Account types and balances (e.g., Checking, Savings, Foreign Currency)
- Risk classification, credit card usage, and other financial indicators

---

## 🔍 EDA Workflow

The notebook is organized into the following sections:

### 1. Univariate Analysis
- Distribution of categorical and numerical features using `sns.countplot()` and histograms.
- Frequency charts for variables like `GenderId`, `Occupation`, and `Properties Owned`.

### 2. Bivariate Analysis
- Comparisons between variables using grouped bar plots.
- Examples: `Income Band` vs `Risk Weighting`, `Loyalty Classification` vs `Fee Structure`.

### 3. Numerical Analysis
- Correlation matrix to identify relationships between numerical features.
- Use of `.describe()` and `.corr()` to summarize distributions and interdependencies.

### 4. Heatmaps
- Heatmap visualization of correlation using `seaborn.heatmap()` to detect strong positive/negative associations.

### 5. Insights
- High correlation observed between account types (e.g., checking and savings).
- Loyalty and income patterns influence credit behavior and risk profile.

---

## 🛠 Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- NumPy
- Jupyter Notebook

---

## ✅ Output

The notebook generates:
- Multiple countplots and bar plots
- A correlation heatmap
- Statistical summaries
- A final list of key insights

---

