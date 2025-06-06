# 📈 Time Series Forecasting of U.S. Industrial Production
This project focuses on comprehensive time series analysis and forecasting of U.S. Industrial Production data using a combination of statistical techniques and visualization tools. The goal was to uncover long-term trends, seasonal patterns, macroeconomic shocks, and forecast future movements with high confidence.

The analysis incorporates STL decomposition, Exponential Smoothing, and SARIMA modeling to dissect the complex dynamics of industrial output over time. Visualization was done using Seaborn and Matplotlib, with an automated pipeline for generating insights and tracking anomalies.

# 🔍 Key Highlights
📊 Advanced Time Series Modeling
- Applied STL decomposition to separate trend, seasonal, and residual components from monthly production data.
- Utilized Exponential Smoothing and SARIMA (Seasonal ARIMA) for robust forecasting and model comparison.
- Achieved reliable forecasts for upcoming quarters with 95% confidence intervals.

# 🔁 Seasonal Cycle Discovery
- Identified structural 6-month seasonal cycles with an amplitude of 12.3%, representing predictable production fluctuations.
- Forecasted a Q1 2025 contraction followed by a June recovery, supported by historical patterns and seasonal behavior.

# 📉 Recession & Anomaly Detection
- Detected major macroeconomic shocks including:

   - The 2008 financial crisis (observed -23.7% production drop).
   - The COVID-19 collapse in April 2020 (-16.5% month-over-month).

- Used 3σ thresholds on residuals to develop a signal-based recession alert system, achieving 85% accuracy in identifying recession periods.

# 📈 Post-Pandemic Recovery Trends
- Analyzed the normalization and recovery phase (2021–2023) following COVID-19.
- Identified a 4.2% recovery rate, indicating an outperformance over pre-pandemic production levels.

# ⚙️ Automated Reporting and Visualization
- Built an automated reporting pipeline using Matplotlib and Seaborn.
- Visual outputs include:

   - Trend and seasonality decomposition.
   - Anomaly and shock detection.
   - Forecast visualizations with confidence bands.
   -Rolling averages and residual plots.

# 🛠 Tools & Libraries Used
- Python
- Pandas & NumPy – Data manipulation and transformation
- statsmodels – Time series modeling (SARIMA, Exponential Smoothing)
- Matplotlib & Seaborn – Custom visualizations
- SciPy – Statistical computation
- Jupyter Notebook – Analysis documentation and experiments





