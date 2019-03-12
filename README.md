# Predicting time series sales with GBM.

Project for Patrick Hall's Machine Learning Class, GWU 2018.

From https://www.kaggle.com/c/competitive-data-science-predict-future-sales.

Completed with Austin Frazer, who is currently #9 on the leaderboard. https://github.com/austinfrazer

The competition was focused on predicting the sales for a software firm with a time-series dataset consisting of daily sales data. The goal is to predict the total sales for every product and store for the coming month. I am in charge of the modeling part basically. The first step is conducting data preparation and variable selection with visual analysis supported by statistical methods and charts. The second step is a customized feature engineering for variables and creating a group of lagging factors reflect the trend and seasonality. The last step is the model part, I have predicted sales with Gradient Boosting Machine after parameter tuning and achieved an RMSE of 0.7954. The project was completed successfully as the result achieved a high ranking, but looking back, I have realized that there are some improvements that could be made to provide a better explanation and logic like adding a part of grid search to discover the optimal solution for the model
