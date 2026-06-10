# Thiranex Internship — Task 3
## House Price Prediction | Predictive Analytics Using Historical Data

### Overview
A complete machine-learning pipeline that predicts residential house prices using **Linear Regression** on an 8-feature dataset of 500 records.

### Results
| Metric | Value |
|--------|-------|
| R² Score | 0.9825 |
| MAE | $14,046 |
| RMSE | $17,491 |
| Train/Test Split | 80% / 20% |

### Project Structure
```
thiranex_task3/
├── house_prices.csv                  # Dataset (500 records, 9 columns)
├── House_Price_Prediction.ipynb      # Jupyter Notebook (full ML pipeline)
├── Task3_Report.pdf                  # 7-page PDF report
├── chart1_actual_vs_predicted.png    # Visualization 1
├── chart2_feature_importance.png     # Visualization 2
├── chart3_residuals.png              # Visualization 3
└── README.md
```

### How to Run
```bash
# Install dependencies
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

# Launch notebook
jupyter notebook House_Price_Prediction.ipynb
```

### Features Used
- `Area_sqft` — Living area in square feet
- `Bedrooms` — Number of bedrooms
- `Bathrooms` — Number of bathrooms
- `Age_years` — Property age
- `Garage_spaces` — Garage parking spaces
- `Dist_School_km` — Distance to nearest school
- `Dist_City_km` — Distance to city centre
- `Crime_Rate` — Local crime rate index

### ML Pipeline Steps
1. Data loading and exploration
2. Missing value check & data cleaning
3. Exploratory Data Analysis (EDA)
4. Feature scaling (StandardScaler)
5. Train/Test split (80/20)
6. Linear Regression model training
7. Evaluation (R², MAE, RMSE)
8. Visualisations (3 charts)

### Tech Stack
Python · pandas · NumPy · scikit-learn · matplotlib · seaborn
