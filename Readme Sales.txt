1️ Data Preprocessing
	Converts Order_Date into a proper datetime format
	Aggregates monthly sales data for trend analysis
	Splits the dataset into training (80%) and testing (20%)

2️ Interactive Visualizations
	Monthly Sales Trends (Interactive Plotly Line Chart)
	Sales Distribution (Histogram + KDE for understanding revenue spread)
	Monthly Sales Heatmap (Seasonal trend detection)
	Sales by Category & Sub-Category (Revenue comparison)
	Geographic Sales Analysis (Choropleth map for sales by state)

3️ Time Series Analysis & Forecasting
	ACF & PACF Plots (To analyze autocorrelations in sales data)
	Auto ARIMA Order Selection (Using pmdarima)
	ARIMA Model for Forecasting (Trained on historical data)
	Interactive Forecast Plot (Actual vs Predicted sales)
	Model Evaluation (Mean Absolute Error & RMSE Calculation)