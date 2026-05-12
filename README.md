# Employee Churn Prediction Model

End-to-end machine learning pipeline for predicting employee churn using HR, performance, and workplace satisfaction data. Built as a demonstration of classification modeling, feature engineering, and data visualization in Python.

## Overview

Uses three source datasets — employee records, performance evaluations, and workplace satisfaction scores — joined and engineered into a feature set for binary churn classification. Includes exploratory data analysis, statistical profiling, and model evaluation.

## Data

| File | Rows | Columns | Description |
|---|---|---|---|
| `data/employee_main_file.csv` | 2,001 | 20 | Core HR attributes (age, tenure, department, salary, etc.) |
| `data/employee_performance_evals.csv` | 8,486 | 3 | Historical performance evaluation scores |
| `data/employee_workplace_sat_scores.csv` | 8,004 | 4 | Workplace satisfaction survey results |

## Tech Stack
- Python 3
- `pandas`, `numpy` — data manipulation
- `scikit-learn` — modeling and evaluation
- `plotly`, `cufflinks` — interactive visualizations
- `scipy` — statistical analysis

## Running the Notebook

```bash
git clone https://github.com/Michael-Keen-MS/Churn-Prediction-Model.git
cd Churn-Prediction-Model
jupyter notebook Employee_Churn_Prediction_Model.ipynb
```

All data is included in the `data/` folder — no external files required.
