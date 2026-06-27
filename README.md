<h1 align="center">👥 Customer Demographics Study</h1>
<h3 align="center">CODTECH IT Solutions — Data Analytics Internship |</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-9cf?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 👤 Intern Information

| Field | Details |
|---|---|
| **Intern Name** | Dhananjay Gope |
| **Intern ID** | CITS2681 |
| **Company** | CODTECH IT Solutions Pvt. Ltd |
| **Domain** | Data Analytics |
| **Task** | Customer Demographics Study |
| **Mentor** | Neela Santhosh Kumar |
| **Duration** | 4 Weeks |

---

## 📌 Objective

Perform a comprehensive demographic analysis of customer data to uncover patterns across gender, age groups, income levels, education, geography, and purchase behaviour. The study helps businesses understand their customer base and craft targeted strategies.

---

## 📁 Project Structure

```
Task-_Customer_Demographics_Study/
│
├── Customer_Demographics_Study.ipynb   # Main Jupyter Notebook
├── customer_demographics.csv           # Customer dataset (100 records)
└── README.md                           # Project documentation
```

---

## 📊 Dataset Description

The dataset contains **100 customer records** covering diverse demographics across Indian cities and states, with the following columns:

| Column | Description |
|---|---|
| `Customer_ID` | Unique customer identifier |
| `Age` | Age of the customer |
| `Gender` | Male / Female |
| `City` | City of residence |
| `State` | State of residence |
| `Education` | Education level (Undergraduate / Graduate / Post Graduate) |
| `Occupation` | Customer's profession |
| `Income_Level` | Income bracket (Low / Medium / High) |
| `Marital_Status` | Single / Married |
| `Children` | Number of children |
| `Purchase_Category` | Primary purchase category |
| `Annual_Spend` | Total annual spending in ₹ |
| `Loyalty_Score` | Customer loyalty score (0–100) |
| `Membership_Type` | Basic / Silver / Gold / Platinum |
| `Years_as_Customer` | Duration of customer relationship |

### Purchase Categories Covered
`Electronics` · `Clothing` · `Food & Grocery` · `Healthcare` · `Jewellery` · `Home Decor` · `Books & Stationery`

---

## 🛠️ Technologies Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, grouping, and aggregation |
| `numpy` | Numerical computations and correlation |
| `matplotlib` | Charts, bar plots, scatter plots |
| `seaborn` | Heatmaps and statistical visualizations |

---

## 📈 Analysis Performed

1. **Data Loading & Inspection** — Shape, column types, sample rows
2. **Data Quality Check** — Null values, duplicates, unique value counts
3. **Feature Engineering** — Age group binning (18–25, 26–35, 36–45, 46–55, 56–65, 65+)
4. **Gender Distribution** — Count pie chart + average spend by gender
5. **Age Group Analysis** — Customer count and average spend per age group
6. **Income Level & Membership Analysis** — Spend comparison across income and membership tiers
7. **Purchase Category Preference** — Count and average spend per category
8. **Education & Marital Status Analysis** — Spending patterns by education and relationship status
9. **Loyalty Score vs Annual Spend** — Scatter plot with trend line and correlation coefficient
10. **State-wise Analysis** — Top 10 states by customer count and average spend
11. **Correlation Heatmap** — Numerical feature correlation matrix
12. **Customer Segment Summary Table** — Cross-tabulation by Membership × Income Level
13. **Key Insights & Business Recommendations** — Actionable findings

---

## 📌 Key Insights

- 🏆 **Electronics** is the most popular purchase category; **Jewellery** has the highest average spend
- 📅 **26–45 age group** forms the largest and most valuable customer segment
- 💳 **Platinum members** show the highest loyalty scores (avg ~94/100)
- 📈 Strong positive correlation between **Loyalty Score** and **Annual Spend**
- 🎓 **Post Graduate** customers spend significantly more than other education groups
- 👨‍👩‍👧 **Married customers** with children tend to spend more on essentials (Food, Healthcare)

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/[your-github-username]/[repo-name].git

# 2. Navigate to Task 2 folder
cd Task-2_Customer_Demographics_Study

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn notebook

# 4. Launch Jupyter Notebook
jupyter notebook Customer_Demographics_Study.ipynb
```

---

## 🏢 About the Internship

This project was completed as **Task** of the **CODTECH IT Solutions Data Analytics Virtual Internship**, as part of the mandatory internship curriculum requirement. The internship is a 4-week program covering key concepts in data analytics using Python.

---

<p align="center">
  <b>Made with ❤️ by Dhananjay Gope | CODTECH IT Solutions Pvt. Ltd.</b>
</p>
