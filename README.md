# Walmart Sales Data Analysis (EDA)

This project explores the Walmart Sales dataset using Exploratory Data Analysis (EDA) to identify the main factors affecting weekly sales. The analysis focuses on sales trends, economic indicators, seasonality, and correlations between variables using statistical analysis and data visualization.

## Key Insights
- Weekly sales are mostly concentrated between 0.5M and 2.5M.
- Temperature, CPI, and Unemployment show a negative relationship with sales.
- Fuel Price has a very weak positive correlation with weekly sales.
- Sales increased during late 2011 and 2012, showing seasonal shopping trends.

## Statistical Model
```text
Weekly_Sales = β0 - β1(Temp) - β2(CPI) - β3(Unemployment) + β4(Fuel_Price) + ε
```

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
