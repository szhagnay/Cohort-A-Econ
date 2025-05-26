<p align="center">
  <img src="assets/cohort_a_econ_banner.png" alt="Cohort-A Econ Banner" width="80%">
</p>

---
# 📦 National & International Economic Insight & EDA Project  
## Cohort-A Econ | End-of-Phase Team Project  
**Contributors:** James Ceus, Jessenia Diaz, Fari Lindo, Bakari Sibert, Sherla Zhagnay

   **Last Updated:** 2025-25-2025  

---

## 📚 Introduction
Our team has just secured an international contract, giving our consultants the exciting opportunity to relocate overseas. For many, this may be their first time living abroad—and while the potential tax benefits are enticing, there’s still a lot of uncertainty around what relocation would actually look like in practice.

Thankfully, through our Innovation Fellowship, consultants have already gotten a taste of work-life dynamics in various global locations. Whether based in South Korea, Brazil, or Vancouver, they’ve provided localized insights and strategic recommendations to clients, gaining first-hand knowledge of different economic landscapes.

Now, as we enter Phase 2 of the fellowship, many consultants are considering where they might want to move—regardless of whether they stay on a data analytics track. To support these decisions, our team is diving into key analytical questions that explore the relationship between income, cost of living, and economic health across regions.

This project aims to explore the current and historical economic conditions of the United States and the Broader World through exploratory data analysis (EDA), Statistical Methods, and visualizations from real data.

We are investigating economic **disparities**, **liquidity trends**, **spending behavior**, and **cost of living pressures** on the American population and the Borader World using two main datasets:

- ##### **Dataset 1:** `Cost_of_Living_and_Income_Extended.csv`
- ##### **Dataset 2:** `US_macro_micro_index.csv`

## Dataset Dictionary
### Cost_of_Living_and_Income_Extended.csv

- **`Country`:** Name of the country.
- **`Year`:** Year of the data recored.                     
- **`Average_Monthly_Income`:** Average monthly income in local currency or USD (check source).
- **`Cost_of_Living`:** Composite cost of living index or total monthly average expenses.
- **`Housing_Cost_Percentage`:** Percentage of income spent on housing.
- **`Tax_Rate`:** Average effective income tax rate (as a percentage).
- **`Savings_Percentage`:** Estimated percentage of income that goes into savings.
- **`Healthcare_Cost_Percentage`:** Percentage of income spent on healthcare.
- **`Education_Cost_Percentage`:** Percentage of income spent on education.
- **`Transportation_Cost_Percentage`:** Percentage of income spent of transportation.                         
- **`Region`:**  Geographic region (e.g., North America, South America, Europe, etc.).                                             

### US_macro_micro_index.csv
- **`nominal_disposable_personal_income_DSPI.csv`:** Total personal income after taxes (not adjusted for inflation). Useful for examining general liquidity available to the population.
  - **Units**: Billions of Dollars
- **`real_disposable_personal_income_percapita_A229RX0.csv`:** Inflation-adjusted income per person. Useful for measuring real purchasing power and income disparity analysis.
  - **Units**: Chained 2017 Dollars per Person 
- **`real_personal_consumption_expenditures_PCEC96.csv`:** Measures inflation-adjusted consumer spending. Useful for analyzing economic activity in areas like housing, food, and healthcare.
  - **Units**: Billions of Chained 2017 Dollars
- **`total_personal_income_pi.csv`:** Total income received before taxes. Useful for examining economic growth, employment, and estimating tax burden when compared to DSPI.
  - **Units**: Billions of Dollars

## 🔗 External Tools & Resources

**Kaggle Dataset:**

- **Source:** [Cost of Living and Income (Extended)](https://www.kaggle.com/datasets/heidarmirhajisadati/regional-cost-of-living-analysis)

**Federal Reserve Economy Database:**
- [FRED - DSPI](https://fred.stlouisfed.org/series/DSPI)
  - **Series ID**: DSPI
- **Source**: [FRED - A229RX0](https://fred.stlouisfed.org/series/A229RX0)
  - **Series ID**: A229RX0
- **Source**: [FRED - PCEC96](https://fred.stlouisfed.org/series/PCEC96)
  - **Series ID**: PCEC96
- **Source**: [FRED - PI](https://fred.stlouisfed.org/series/PI)
  -  **Series ID**: PI

## 💡 Notes

- 💵 Note: All monetary values are expressed in either inflation-adjusted dollars (real) or nominal dollars, as clearly indicated.
- 📈 Team members are encouraged to contribute visualizations and summary writeups alongside their EDA.
---

## 🔍 Analytical Questions & Team Responses

### 🧠 **James Ceus**
**Question:**  
*How does income correlate with specific components of the cost of living (e.g., housing affordability, food prices) across different regions?*

**Response:**  
<!-- Write your notes, analysis, or findings here -->
- Used heatmap to analyze correlation between income & housing, food, transportation
- Found strongest correlation with housing costs in North America (r = -0.4)
- Next step: Run linear regression to quantify income impact on cost drivers

---

### 🧠 **Bakari Sibert**
**Question:**  
*With a focus on the United States, how does the distribution of income compare to the distribution of cost of living?*

**Response:**  
<!-- Add EDA insights or visualizations -->
- Theres not a strong correlation between to total income earned and cost of living because one is a micro economic factor and one is a macro with potentially different inputs.
- Noticed that lower-income brackets spend disproportionately more on housing
- Cost of living varies widely by region—Midwest vs West Coast especially stark

---

### 🧠 **Fari Lindo**
**Question:**  
*What’s the overall economic health of Americans—how much liquidity do Americans have?*

**Response:**  
- The U.S. has seen steady personal income growth, doubling over the last two decades.
- Despite temporary income spikes during the 2020–2021 pandemic period, long-term trends show consistent wage increases and economic recovery post-COVID. 
- However, real purchasing power has flattened recently due to inflation, even as nominal income rises.
- The seasonal pattern also matters: 
  - income typically peaks in March and December (bonuses, refunds) and dips in summer months (July–August).
- Most individuals fall within the $40K–$50K disposable income range, highlighting income concentration in the mid-tier.
- The Wealth Gap doesn't seem to be narrowing--majority of Americans are earning between $40k-$50k range and a small amount of individuals earn ~$60k. 

---

### 🧠 **Jessenia Diaz**
**Question:**  
*In what ways have Americans’ spending patterns changed over time, and how do trends in expenditures reflect those shifts?*

**Response:**  
- Expendiutures rose over time...
- Plotting trends over time (2010–2023) using line graphs

---

### 🧠 **Sherla Zhagnay**
**Question:**  
*Does the relationship between income and cost of living across global regions (e.g., North America, South America, Europe) influence Americans’ spending habits, financial liquidity, and overall economic well-being over time?*

**Response:**  
- Compared U.S. with similar economies in Europe
- Americans tend to spend more out-of-pocket on healthcare than Europeans
- Global inflation trends seem to impact savings behavior

---

## General Consensus: 
**We recommend:** 
   - If thinking about moving to the US, target growing sectors like tech, healthcare, and green energy for higher earning potential.
   - Plan financially for summer months, when income tends to dip.
   - Factor in regional costs (housing, transportation) when evaluating salaries.
   - Look beyond salary—real income and cost of living determine true financial well-being.
   - For new immigrants or job seekers, aim to negotiate based on inflation-adjusted value, not nominal pay alone.
  - The U.S. offers a resilient and growing economy, but smart financial planning is key to turning opportunity into long-term success.

## 👥 Maintainers

This project is part of a collaborative effort by **TKH for TEPP Group Project**. Developed by James Ceus, Jessenia Diaz, Fari Lindo, Bakari Sibert, and Sherla Zhagnay.

For questions, please contact: `sjzhagnay3@gmail.com` or open an issue in the repo.
