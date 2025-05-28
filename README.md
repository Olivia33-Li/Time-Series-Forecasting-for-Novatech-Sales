# 📈 CPI Forecasting & Interest Rate Analysis

This project analyzes the relationship between Australia’s Consumer Price Index (CPI) and interest rates, and applies time series forecasting models to predict future CPI trends. It highlights strong data preparation, entry accuracy, and model evaluation practices.

## 📌 Project Overview

- **Objective**: Forecast future CPI values and explore how they relate to interest rate trends.
- **Data Sources**:
  - Australian Bureau of Statistics (ABS) – CPI data
  - Reserve Bank of Australia (RBA) – Interest rate data
- **Time Range**: 2005–2024 (quarterly data)

## 🔧 Tools and Technologies

- **Languages**: Python
- **Libraries**: pandas, NumPy, matplotlib, seaborn, scikit-learn, statsmodels, prophet
- **Methods**: Time series forecasting, model comparison, data validation, error checking

## 📊 Project Workflow

### 1. Data Entry & Cleaning
- Loaded CSV data and converted dates into quarterly datetime format
- Checked for and removed duplicate entries
- Ensured data integrity before modeling

### 2. Exploratory Data Analysis (EDA)
- Plotted CPI and interest rate trends over time
- Used seasonal decomposition to analyze patterns
- Investigated correlations between inflation and interest rate shifts

### 3. Model Building
- **Holt-Winters**: Captures seasonal and trend patterns
- **SARIMA**: Used AIC and PACF/ACF to select parameters
- **Prophet**: Deployed Facebook's model for robust time-based prediction

### 4. Model Evaluation
- Applied time series cross-validation using `TimeSeriesSplit`
- Compared models using Mean Squared Error (MSE)
- Selected the best model for 12-month CPI forecast

### 5. Visualization
- Generated line plots with forecasted CPI trends
- Highlighted forecast ranges and potential implications for economic planning

## ✅ Key Highlights

- Applied structured data entry and cleaning using pandas and Excel
- Built a reliable forecasting pipeline to support policy analysis
- Ensured data accuracy and reproducibility across all steps
- Demonstrated proficiency in both statistical modeling and practical data handling
