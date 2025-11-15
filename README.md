# EV-Adoption-Analysis
Analysis of ~220K EV registrations using Python and ML to uncover adoption patterns, key predictors, and insights for EV policy and market growth.


This project analyzes U.S. electric vehicle (EV) registrations to understand adoption patterns across regions and evaluate how vehicle characteristics and policy-related factors influence EV growth.

## Project Overview

- Analyzed ~220K EV registration records using Python (pandas, scikit-learn) and SQL.
- Modeled EV adoption using:
  - Linear Regression
  - Random Forest Regression
  - K-Means clustering with PCA
- Identified key adoption drivers such as:
  - Electric range
  - Model year
  - Vehicle type / class
- Findings showed that **electric range was significantly more predictive of adoption (≈47% stronger effect) than model year** and revealed **three major EV adoption clusters**.

## Tech Stack

- **Languages:** Python, SQL
- **Python Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Data:** Electric Vehicle Population dataset (registration-level records)
- **Environment:** Jupyter Notebook, optional AWS for data storage/processing

## Repository Structure

```text
EV-Adoption-Analysis/
│── README.md
│── data/
│   └── ev_population_data.csv
│── notebooks/
│   └── ev_adoption_analysis.ipynb
│── reports/
│   ├── EV_Adoption_Project_Report.pdf
│   └── ev_adoption_analysis.html
│── src/
│   └── (optional scripts)
│── visuals/
│   └── (plots and figures)
│── requirements.txt
└── LICENSE
