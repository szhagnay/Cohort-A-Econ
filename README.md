<p align="center">
  <img src="assets/cohort_a_econ_banner.png" alt="Cohort-A Econ Banner" width="80%">
</p>

---
# 📦 National & International Economic Insight & EDA Project  
## Cohort-A Econ | End-of-Phase Team Project  
**Contributors:** James Ceus, Jessenia Diaz, Fari Lindo, Bakari Sibert, Sherla Zhagnay

## **Project Title:** Understanding the Economic Health of Americans and the Broather World 
   **Last Updated:** 2025-05-20  
## **Team Members:** James Ceus, Jessenia Diaz, Fari Lindo, Bakari Sibert, Sherla Zhagnay

---

## 🧠 Project Purpose

This project aims to explore the current and historical economic conditions of the United States and the Broader World through exploratory data analysis (EDA), Statistical Methods, and visualizations.

We are investigating economic **disparities**, **liquidity trends**, **spending behavior**, and **cost of living pressures** on the American population and the Borader World using two main datasets:

- **[Kaggle: Cost of Living & Income Dataset (Extended)](PLACEHOLDER_FOR_LINK)**
- **[US Macro-Micro Index Dataset](PLACEHOLDER_FOR_LINK)** — a monthly panel of key FRED economic indicators

---

## 🔍 Analytical Questions

### ✳️ Group-level Investigative Focus
**What is the overall economic health of Americans and Broder world?**

1. How does income correlate with specific components of the cost of living (e.g., housing affordability, food prices)?
2. How much liquidity do Americans have? 
2. What does disposable income look like over time? Are the regional disparities(eg., North American Region, etc...)?
3. What are people’s spending habits over time — are they spending more or less?
4. How can we use cost of living or expenditure trends to understand the spending behavior of Countries of the world (eg., the cost of housing, food, transportation, etc..)?
5. Are Americans enjoying economic growth, or is there a decline in earnings?
6. Have certain components of the cost of living increased over time, and if so at what rate?

---

## 🔍 Member Contributions

| Member | Questions |
|--------|-----------|
| **James Ceus**     | - How does income correlate with specific components of the cost of living?<br> - Have some living costs increased faster than income in certain areas? |
| **Jessenia Diaz**  | - How did import/export volumes fluctuate monthly across major East Coast ports in 2024? |
| **Fari Lindo**     | - How are people spending over time?<br> - How much disposable income do Americans have over time?<br> - What does the cost of living look like for North Americans? *(Also built the US Macro-Micro Index dataset)* |
| **Bakari Sibert**  | - Are Americans enjoying economic growth, or is there a decline in earnings? |
| **Sherla Zhagnay** | - How can we use cost of living or expenditure trends to understand the spending behavior of Countries of the world (eg., the cost of housing, food, transportation, etc..)? |

---

## 📊 Kaggle Dataset (Primary)

### **About Dataset**
This dataset provides insights into the cost of living and average monthly income across various countries and regions worldwide from 2000 to 2023.
It includes critical economic indicators such as housing costs, taxes, healthcare, education, transportation expenses, and savings rates. The data is ideal for analyzing economic trends, regional comparisons, and financial planning.

### **Column Descriptions:**
- Country: The name of the country where the data was recorded.
- Region: The geographical region to which the country belongs (e.g., Asia, Europe).
- Year: The year when the data was recorded.
- Average_Monthly_Income: The average monthly income of individuals in USD.
- Cost_of_Living: The average monthly cost of living in USD, including essentials like housing, food, and utilities.
- Housing_Cost_Percentage: The percentage of income spent on housing expenses.
- Tax_Rate: The average tax rate applied to individuals' income, expressed as a percentage.
- Savings_Percentage: The portion of income saved monthly, expressed as a percentage.
- Healthcare_Cost_Percentage: The percentage of income spent on healthcare services.
- Education_Cost_Percentage: The percentage of income allocated to educational expenses.
- Transportation_Cost_Percentage: The percentage of income spent on transportation costs.

## 🧠 Macro-Micro Index Panel (Secondary)
### **About Dataset**
### **Economic Data Documentation**

This dataset includes several key economic indicators from the Federal Reserve Economic Data (FRED) database, prepared for exploratory data analysis on U.S. income and spending trends.

### 1. `nominal_disposable_personal_income_DSPI.csv`
- **Series ID**: DSPI
- **Source**: [FRED - DSPI](https://fred.stlouisfed.org/series/DSPI)
- **Units**: Billions of Dollars
- **Description**: Total personal income after taxes (not adjusted for inflation). Useful for examining general liquidity available to the population.

### 2. `real_disposable_personal_income_percapita_A229RX0.csv`
- **Series ID**: A229RX0
- **Source**: [FRED - A229RX0](https://fred.stlouisfed.org/series/A229RX0)
- **Units**: Chained 2017 Dollars per Person
- **Description**: Inflation-adjusted income per person. Useful for measuring real purchasing power and income disparity analysis.

### 3. `real_personal_consumption_expenditures_PCEC96.csv`
- **Series ID**: PCEC96
- **Source**: [FRED - PCEC96](https://fred.stlouisfed.org/series/PCEC96)
- **Units**: Billions of Chained 2017 Dollars
- **Description**: Measures inflation-adjusted consumer spending. Useful for analyzing economic activity in areas like housing, food, and healthcare.

### 4. `total_personal_income_pi.csv`
- **Series ID**: PI
- **Source**: [FRED - PI](https://fred.stlouisfed.org/series/PI)
- **Units**: Billions of Dollars
- **Description**: Total income received before taxes. Useful for examining economic growth, employment, and estimating tax burden when compared to DSPI.

## ✅ Notes

- All datasets are **monthly** and **seasonally adjusted**.
- Use metadata CSV for provenance tracking and column units.

---

## 📁 Datasets Used

### 📊 Kaggle Dataset (Primary)

- **Name:** Cost of Living and Income (Extended)
- **Source:** [[Regional Cost of Living Analysis
Income and Expense Patterns Worldwide](https://www.kaggle.com/datasets/heidarmirhajisadati/regional-cost-of-living-analysis)]

### 🧠 Macro-Micro Index Panel (Secondary)

- **Name:** `US_macro_micro_index.csv`
- **Description:** Monthly macro and per-capita economic indicators from 1959–2025
- **Data Source(s):**
    - [FRED: DSPI - Disposable Personal Income](https://fred.stlouisfed.org/series/DSPI)
    - [FRED: A229RX0 - Real Disposable Income Per Capita](https://fred.stlouisfed.org/series/A229RX0)
    - [FRED: PCEC96 - Real Personal Consumption Expenditures](https://fred.stlouisfed.org/series/PCEC96)
    - [FRED: PI - Personal Income](https://fred.stlouisfed.org/series/PI)

---

## 🛠️ Planned Features

- 📈 Time-series analysis with rolling trends
- 📊 Visual EDA to answer each member’s questions
- 📍 Map overlays of regional data (TBD)
- 📑 Final presentation and dashboard with insights

---

## 💡 Notes

- All dollar-based figures are inflation-adjusted or noted with nominal units.
- Team members are encouraged to contribute visualizations and summary writeups alongside their EDA.

---

## 👥 Maintainers

This project is part of a collaborative effort by **TKH for TEPP Group Project**.  
Developed by James Ceus, Jessenia Diaz, Fari Lindo, Bakari Sibert, and Sherla Zhagnay.

For questions, please contact: `sherla@email.com` or open an issue in the repo.
