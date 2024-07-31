# Crop-Price-Prediction

This project provides a solution for forecasting the prices of agricultural commodities using a Flask-based web application. It uses historical crop data, rainfall statistics, and decision tree regression models to predict crop prices. The application also visualizes the forecasted data on an interactive web dashboard.

Commodity Data and Forecasting
The application reads commodity data from CSV files, performs regression using a decision tree, and provides methods to get predicted values based on the rainfall and historical data.

Visualization Dashboard
The dashboard displays the forecasted prices for the commodities over the next twelve months and the historical prices for the past twelve months. It includes:

Top Five Winners: Commodities with the highest predicted price increase.
Top Five Losers: Commodities with the highest predicted price decrease.
Individual Commodity Profiles: Detailed forecasts and historical data for each commodity.
