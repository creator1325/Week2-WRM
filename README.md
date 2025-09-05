# Week2-WRM


# 💧 Global Water Consumption – Regression Module 

## Objective
Train a **Linear Regression** model to predict **Total Water Consumption (Billion Cubic Meters)** using sectoral usage, rainfall, and groundwater depletion.

## Dataset
**File:** cleaned_global_water_consumption.csv 
**Columns used:**
- Year
- Agricultural Water Use (%)
- Industrial Water Use (%)
- Household Water Use (%)
- Rainfall Impact (Annual Precipitation in mm)
- Groundwater Depletion Rate (%)
- **Target:** Total Water Consumption (Billion Cubic Meters)

## Requirements
- Python (Colab/Jupyter)
- pandas, numpy, matplotlib, seaborn
- scikit-learn

## How to Run (Google Colab)
1. Open a new Colab notebook.
2. Install deps (if needed):  
   !pip install pandas numpy matplotlib seaborn scikit-learn
3. Upload the CSV:  
   python
   from google.colab import files
   files.upload()  # select cleaned_global_water_consumption.csv


4. Paste and run the **Corrected Regression Code**:

   * Load CSV into `df`
   * Define `features` and `target` as above
   * Train/test split
   * Train `LinearRegression`
   * Evaluate with **R²**, **MAE**, **RMSE**
   * Plot **Actual vs Predicted**

## Outputs

* Metrics printed: **R²**, **MAE**, **RMSE**
* Plot: **Actual vs Predicted Water Consumption**

## Notes

* Column names in code **must** match the dataset exactly.
* This module is **20% of the full project** (ML Step 1: Linear Regression). Further modules (e.g., Random Forest, forecasting, report) come next.

