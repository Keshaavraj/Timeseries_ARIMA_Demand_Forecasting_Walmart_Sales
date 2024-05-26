# SalesInsight: Elevating Retail Strategy through Precise Demand Forecasting (Timeseries Model - ARIMA/SARIMAX) at Walmart 📈💡

## Sales Data Analysis and Forecasting 🛒🔍

This repository hosts a collection of Python scripts designed for comprehensive analysis of sales data, visualization of top-selling items, and precise demand forecasting utilizing SARIMA models. The codebase encompasses feature importance analysis, sales visualization, demand forecasting, and evaluation metrics calculation.

### Project Overview 🚀

The project focuses on optimizing inventory management, particularly at Walmart, through accurate monthly sales forecasting, with emphasis on top-selling items across diverse categories using SARIMAX models. It has achieved notable success, demonstrating low mean absolute error (MAE) particularly in the Hobbies category. The insights garnered from this project hold significance in guiding decisions pertaining to pricing strategies, inventory management, and marketing endeavors, thereby augmenting overall sales performance through strategic adjustments in pricing, store allocation, and promotional activities.

### Machine Learning Workflow 🤖

#### Data Collection 📊

The project utilizes data extracted from an Excel file, housing sales records categorized into various segments such as FOODS, HOBBIES, and HOUSEHOLD.

#### Data Cleaning 🧹

Prior to analysis and modeling, extensive data cleaning and preprocessing are undertaken. This involves meticulous handling of missing values, ensuring accurate datetime indexing, and aggregating sales data across different time intervals (daily, monthly, quarterly, yearly).

#### Exploratory Data Analysis (EDA) 🔍

EDA plays a pivotal role in identifying top-selling items within each category by grouping data and summing up sales. Visualizations are generated to elucidate sales trends over time for these top-selling items.

#### Machine Learning Training 🎓

The project employs SARIMAX models for demand forecasting of top-selling items. These models are trained on monthly sales data, subsequently generating forecasts for future sales.

#### Model Metrics 📊

To gauge the accuracy of the forecasts, evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) are meticulously calculated.

### Conclusion 📝

Key findings from the project include:

- Positive correlation between selling price and sales across all categories, indicating higher prices lead to increased sales.
- Varied impacts of different stores and states on sales predictions, with some contributing positively while others negatively.
- Identification of certain days of the week exhibiting a negative impact on sales predictions, suggesting lower sales on those days.

These insights serve as valuable inputs for making informed decisions regarding pricing strategies, inventory management, and marketing efforts to optimize sales within each category. Strategic adjustments in pricing, store allocation, and promotional activities can help mitigate the negative impacts identified and enhance overall sales performance.
