# BankX — Banking Dashboard

<p align="center">
  <strong>End-to-end data analysis → MySQL → EDA → Power BI</strong>
</p>

---

## Overview

**BankX** is an interactive **Banking Dashboard** built with Power BI. It covers the full lifecycle: data cleaning, transformation, exploratory analysis, and visualization.

| | |
|---|---|
| **Columns** | 24 |
| **Database** | MySQL |
| **Stack** | SQL, DAX, Power BI |

---

## Workflow

```
Data  →  MySQL  →  Cleaning & Prep  →  EDA  →  Power BI Dashboard
```

---

## Data Cleaning & Prep

- **Income bands:** `Low` · `Mid` · `High` (Power BI conditional columns)
- **Categorical cleanup:** gender, nationality, branch codes → readable labels
- **Mappings:** `'1'` → Male, `'2'` → Female; branch codes → branch names

---

## Exploratory Data Analysis

**Categorical:** Gender, Nationality  

**Numerical:** Credit Card Balance, Bank Loans, Bank Deposits, Checking Account, Saving Account, Estimated Income, Superannuation Savings

---

## Main insight

Strong positive correlation among **Bank Deposits**, **Checking Account**, **Saving Account**, and **Foreign Currency Account** — high balance in one tends to align with high balances in others.

---

## Dashboard (4 pages)

| # | Page | Role |
|---|------|------|
| 1 | Home | Summary and main KPIs |
| 2 | Loan Analysis | Loan mix and segments |
| 3 | Deposit Analysis | Balances, deposit mix, correlations |
| 4 | Summary | EDA takeaways and demographics |

---

## Screenshots

### 1. Home  
> Summary statistics and main visuals.

<img src="powerbi/page1_home.png" alt="Page 1 - Home" width="700"/>

### 2. Loan Analysis  
> Loan distribution and customer segments.

<img src="powerbi/page2_loan_analysis.png" alt="Page 2 - Loan Analysis" width="700"/>

### 3. Deposit Analysis  
> Account balances and correlation patterns.

<img src="powerbi/page3_deposit_analysis.png" alt="Page 3 - Deposit Analysis" width="700"/>

### 4. Summary  
> Correlations and demographic trends.

<img src="powerbi/page4_summary.png" alt="Page 4 - Summary" width="700"/>

---

## Tools

- **Database:** MySQL  
- **BI:** Power BI  
- **Languages:** SQL, DAX

---

## Takeaways

- Data wrangling with SQL  
- Power BI conditional columns  
- EDA and insight extraction  
- Multi-page dashboards for reporting
