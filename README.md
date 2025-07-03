# 🏦 Banking Analysis

A data analysis project focused on customer segmentation and risk assessment using real-world-style banking data. The analysis provides insights into financial behavior, helps identify high-value customers, and supports risk mitigation strategies.

---

## 📌 Objective

- Analyze customer behavior based on banking features  
- Identify loyal and high-deposit clients  
- Understand risk-weight distribution across demographics  
- Support data-driven decisions for banking services

---

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **pandas**, **numpy**
- **matplotlib**, **seaborn**

---

## 📂 Dataset

- **File:** `Banking.csv`  
- The dataset contains information on customer deposits, savings, checking accounts, business lending, risk weighting, loyalty classification, and more.

---

## 📊 Analysis Workflow

1. **Data Preprocessing**
   - Convert financial columns (e.g. deposits, savings) to numeric types
   - Handle missing values and type conversions

2. **Feature Engineering**
   - Calculate total wealth = deposits + savings + checking + business lending
   - Segment data by geography, age, and property ownership

3. **Exploratory Data Analysis (EDA)**
   - Visualize distributions of financial features
   - Analyze risk weighting across different occupations
   - Compare loyalty classification with fee tiers

4. **Insights**
   - Identify top customers based on total deposits
   - Analyze risk patterns for better targeting
   - Assess financial behavior by age and region

---

## 📈 Sample Visualizations

- Wealth distribution among customers  
- Bank deposits vs. age (scatter plot)  
- Risk weighting by occupation and region  
- Loyalty classification by monthly fee tier  
- Business lending vs. deposits  
- Deposit trends by property ownership and risk score

> 📍 _All visualizations are available in the notebook: `banking analysis.ipynb`_

---

## 🚀 Getting Started

To run this project locally:

```bash
git clone https://github.com/Manoj-B-S/Banking-analysis.git
cd Banking-analysis

# (Optional) create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install necessary packages
pip install -r requirements.txt
