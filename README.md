# Airline Demand Forecast & Route Profitability Analysis ✈️

## 📌 Overview
This project analyzes airline passenger demand and estimates route profitability using historical flight data. It applies **time series forecasting** and **data analytics** to help optimize airline **scheduling, pricing, and network planning** — aligning closely with the decision-making needs of the aviation industry.

## 🎯 Business Relevance
Accurate demand forecasting enables airlines to:
- Optimize **flight schedules** and **route frequency**
- Adjust **ticket pricing** based on seasonal trends
- Identify **high-value and low-performing routes**
- Support **strategic network expansion** decisions

## 📂 Dataset
- **Source:** Public airline datasets (OpenFlights, FAA, or equivalent)
- **Time Period:** Example — 2018–2023
- **Key Fields:** Origin, Destination, Month, Year, Passengers, Revenue (if available)

## 🛠 Tools & Technologies
- **Python:** pandas, numpy, scikit-learn, Prophet, matplotlib, seaborn
- **Visualization:** Tableau / Power BI for interactive dashboards
- **Data Processing:** Jupyter Notebook / Google Colab

## 📊 Methodology
1. **Data Cleaning & Preparation**
   - Load CSV files
   - Handle missing values and inconsistent route codes
   - Create route identifier (e.g., `JFK-LAX`)
2. **Exploratory Data Analysis (EDA)**
   - Top N most profitable / highest-demand routes
   - Seasonal demand patterns & anomalies
3. **Time Series Forecasting**
   - Fit **Prophet** model for each route
   - Forecast **12 months ahead** passenger demand
4. **Profitability Estimation**
   - Calculate total revenue per route (or passenger volume proxy)
   - Rank routes by profitability
5. **Visualization & Reporting**
   - Static plots in Python
   - Interactive dashboards in Tableau / Power BI

## 📈 Key Insights (Example)
- Route `JFK-LAX` shows **consistent seasonal spikes** during summer and winter holidays.
- Route `ATL-ORD` is a **steady performer** with minimal volatility, ideal for capacity optimization.
- Low-demand routes present **opportunities for code-share agreements** instead of direct service.

## 🚀 How to Run
```bash
# Clone repo
git clone https://github.com/harsheetasys/airline-demand-forecast.git
cd airline-demand-forecast

# Run analysis notebook
jupyter notebook airline_forecast.ipynb

Dataset Link:https://www.kaggle.com/datasets/shaivyac/us-airline-dataset
