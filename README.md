# COVID-19 Dataset — Exploratory Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the supplied early COVID-19 dataset.

### Dataset columns
- `Province/State`
- `Country`
- `Date last updated`
- `Confirmed`
- `Suspected`
- `Recovered`
- `Deaths`

## EDA Covered
1. Dataset shape and structure
2. Data types
3. Missing-value analysis
4. Duplicate-value analysis
5. Descriptive statistics
6. Numerical distributions
7. Boxplots/outlier view
8. Country/label frequency
9. Highest confirmed-case observations
10. Time-series analysis
11. Latest-snapshot regional analysis
12. Confirmed vs suspected relationship
13. Correlation analysis
14. Key findings and conclusion

## Main Data-Quality Notes
- The supplied file contains **368 rows and 7 columns**.
- There are **19 exact duplicate rows**.
- Several columns contain substantial missing values.
- Country labels are not completely standardized, so the EDA preserves the original labels.
- Exact duplicates are removed only in analysis copies when aggregation could otherwise double-count records.

## How to Run
1. Upload/clone this folder into Jupyter Notebook, JupyterLab, Google Colab, or VS Code.
2. Open `COVID19_EDA.ipynb`.
3. Make sure `2019_nC0v_20200121_20200126_SUMMARY.csv` is in the same folder.
4. Run all cells.

## Technologies
Python, Pandas, NumPy, Matplotlib, Jupyter Notebook.

## Files
- `COVID19_EDA.ipynb` — complete EDA notebook
- `2019_nC0v_20200121_20200126_SUMMARY.csv` — supplied dataset
- `requirements.txt` — required Python packages
