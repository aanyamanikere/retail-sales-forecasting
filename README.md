# Retail Store Sales - Time Series Forecasting

This repository implements a machine learning forecasting to predict daily grocery sales. It focuses on isolating long-term trends and modeling complex seasonal behaviours using linear regression.

## Key Features
* **Deterministic Trends:** Implemented cubic polynomial trend tracking to model non-linear long-term growth and shifts.
* **Seasonality Tracking:** Combined weekly day-of-week indicators with smooth monthly Fourier components to map calendar abnormalities.
* **Lag Features:** Structured target-lag arrays using Pandas alignment to allow the regression model to use historical data.

## Technologies Used
* Python 3
* Pandas & NumPy (Data manipulation and matrix alignment)
* Scikit-Learn (LinearRegression modeling)
* Statsmodels (DeterministicProcess & CalendarFourier)
* Matplotlib & Seaborn (Trend visualization)
