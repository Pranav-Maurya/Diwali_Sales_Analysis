# Diwali Sales Analysis

Project repository for analyzing Diwali sales data. This project contains the sales dataset and two Jupyter notebooks with exploratory data analysis and visualizations.

**Files included:**
- **Dataset:** [Diwali Sales Data.csv](Diwali%20Sales%20Data.csv)
- **Notebooks:** [Diwali_Sales_Analysis.ipynb](Diwali_Sales_Analysis.ipynb)

Overview
- This repository explores Diwali sales transactions (customers, products, amounts, demographics) using Python and Jupyter notebooks. Analyses include data cleaning, aggregation, and visualizations to uncover sales patterns by state, product category, age group, and more.

Getting started
1. Clone the repository:

```
git clone <your-repo-url>
cd Python_Diwali_Sales_Analysis-main
```

2. Create a Python environment and install common data libraries (example):

```
python -m venv .venv
.\.venv\Scripts\activate
pip install pandas matplotlib seaborn plotly notebook
```

3. Open the notebooks in Jupyter or VS Code and run cells:

```
jupyter notebook
```

Notebooks
- `Diwali_Sales_Analysis.ipynb` — primary analysis and visualizations.
- `Diwali_Sales_Analysis copy.ipynb` — working copy / alternate exploration.

Dataset
- The dataset `Diwali Sales Data.csv` contains transactional rows with columns such as `User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`, and `Status`.

Tips
- If you see encoding issues (e.g., special characters in state names), open the CSV with `encoding='utf-8'` or try `encoding='latin1'` when loading with pandas.
- Some `Amount` values may be missing; handle `NaN`s before aggregations.


