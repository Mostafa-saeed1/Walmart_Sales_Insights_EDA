1 _ Walmart Sales Data Analysis (EDA) This project conducts a comprehensive Exploratory Data Analysis (EDA) on the Walmart Sales dataset to identify key factors influencing weekly revenue. By leveraging statistical techniques and data visualization, the analysis explores the impact of economic indicators, environmental factors, and seasonal trends on retail performance. Analysis Insights

2 _ Data Distribution Analysis 
● Weekly Sales: The values are primarily concentrated between 0.5M and 2.5M. The distribution is right-skewed (positive skewness), indicating the presence of high-value outliers representing exceptional sales weeks. 
● Temperature: Follows an approximately Normal Distribution, with measurements recorded in Fahrenheit. 
● Fuel Price & CPI: Both features exhibit a Bimodal Distribution, suggesting two distinct frequent price levels or economic states within the dataset.
● Unemployment Rate: The distribution is centered around a mean of 8%.
Correlation & Relationships
● Inverse Impact (Negative Correlation): There is a noticeable inverse relationship between Weekly Sales and factors such as Temperature, CPI (Inflation), and Unemployment. As these metrics increase, weekly sales tend to decrease.
● Positive Impact: A very slight positive correlation exists between Fuel Price and Weekly Sales, indicating that sales remained relatively resilient despite fluctuations in fuel costs. 
● Key Predictors: Based on the statistical strength of these relationships, Temperature, CPI, and Unemployment emerge as the most influential variables in the model.
Time Series & Seasonality
● Seasonality Patterns: The analysis reveals a significant increase in sales during the final quarters of 2011 and 2012. This upward trend confirms the presence of seasonality, likely driven by holiday shopping peaks.
Statistical Modeling To describe the relationship mathematically, a Multiple Linear Regression model is proposed: Weekly_Sales = β0 - β1(Temp) - β2(CPI) - β3(Unemployment) + β4(Fuel_Price) + ε ️ Tech Stack & Libraries
● Language: Python 3.8+
● Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scipy.
