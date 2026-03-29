#  E-Commerce Revenue Analysis

An exploratory and explanatory data analysis project investigating what drives revenue in a UK-based online retail store.

##  Project Overview

Using one year of real transaction data (Dec 2010 – Dec 2011), this project answers three key business questions about seasonality, geography, and customer purchasing behavior — with clean visualizations designed for a non-technical audience.

##  Key Questions

1. **Season** — Which months generate the most revenue? Is there a holiday effect?
2. **Geography** — How dominant is the UK, and which other countries matter?
3. **Behavior** — Do customers buy in bulk at low prices, or few items at high prices?

##  Key Findings

-  Revenue peaks in **November at £1.16M** — nearly double the monthly average of £663K — driven by wholesalers stocking up ahead of the Christmas season
- 🇬🇧 The **UK dominates** revenue, but several European countries show significant potential
-  Customer behavior shows a **bulk-buying pattern** at lower unit prices

##  Dataset

| Detail | Value |
|--------|-------|
| Source | [UCI Online Retail Dataset (Kaggle)](https://www.kaggle.com/datasets/carrie1/ecommerce-data) |
| Raw size | 541,909 rows × 8 columns |
| Clean size | 397,884 rows × 11 columns |
| Period | Dec 2010 – Dec 2011 |
| Countries | 37 |
| Unique customers | 4,338 |

**Cleaning steps:** Removed nulls, cancellations (InvoiceNo starting with 'C'), and negative quantities/prices.

##  Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

- **Python** — Data analysis and visualization
- **Pandas** — Data cleaning and aggregation
- **Matplotlib / Seaborn** — Exploratory and explanatory visualizations
- **Jupyter Notebook** — Development and presentation

## 📁 Project Structure

```
ecommerce-revenue-analysis/
│
├── exploration-checkpoint.ipynb    # EDA: univariate, bivariate, multivariate analysis
├── explanatory-checkpoint.ipynb    # Final presentation-ready visualizations
└── README.md
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/muhiaAwad/ecommerce-revenue-analysis.git
   cd ecommerce-revenue-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Start with exploration:
   ```bash
   jupyter notebook exploration-checkpoint.ipynb
   ```

4. Then view the final explanatory analysis:
   ```bash
   jupyter notebook explanatory-checkpoint.ipynb
   ```

## 📝 Part of

**Udacity Data Analyst Nanodegree** — Communicate Data Findings Project
