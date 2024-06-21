# E-commerce Sales Analysis and Forecasting
<img src='CoverECommerce.jpg' />

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Questions Addressed](#Questions-Addressed)
- [Results](#results)
- [Visualizations](#visualizations)
- [Forecasting](#forecasting)
- [Repository Structure](#repository-structure)
- [Conclusion](#conclusion)
- [Contact](#Contact)

## Introduction
This project aims to analyze historical e-commerce sales data to identify trends, understand seasonality, and forecast future sales. The goal is to assist in strategic planning and inventory management.

## Project Overview
1. **Data Collection:** Downloaded historical sales data from the UCI repository.
2. **Data Cleaning:** Removed duplicates, handled missing values, and converted date columns.
3. **Data Aggregation:** Aggregated data by month, product category, and country using SQL.
4. **Exploratory Data Analysis (EDA):** Identified trends, seasonality, and outliers using Python.
5. **Data Visualization:** Created visualizations in Excel and Tableau.
6. **Sales Forecasting:** Applied ARIMA and Prophet models to forecast future sales.
7. **Business Intelligence Report:** Generated a comprehensive report using Tableau or Power BI.
8. **Final Review and Presentation:** Reviewed and prepared the final presentation of the project.
9. **Deployment and Sharing:** Published interactive dashboards and shared reports with stakeholders.
   
## Questions Addressed
1. **What are the monthly and seasonal trends in sales?**
2. **Which product categories generate the highest revenue?**
3. **What is the customer lifetime value (CLV) for different segments?**
4. **What is the total sales specific to a country**

## Results
- Summarized key insights from the analysis.
- Highlighted trends and patterns observed in the sales data.

## Visualizations
1. **What are the monthly and seasonal trends in sales?**
![Monthly Sales Trend](https://github.com/Rehaaaan/E-commerce-Sales-Analysis-and-Forecasting/blob/main/visualizations%2FE-commerce%2FPyImages%2FMonthly%20Sales%20Trend%28ECOMMERCE%29.png)

2. **Which product categories generate the highest revenue?**
![Top Product Categories](https://github.com/Rehaaaan/E-commerce-Sales-Analysis-and-Forecasting/blob/main/visualizations%2FE-commerce%2FExcel%2FHistogram%20of%20TotalSales.png)

3. **What is the customer lifetime value (CLV) for different segments?**
![clv](https://github.com/Rehaaaan/E-commerce-Sales-Analysis-and-Forecasting/blob/main/visualizations%2FE-commerce%2FPyImages%2FQ3a_Py.png)

4. **What is the total sales specific to a country**
![Total sales](https://github.com/Rehaaaan/E-commerce-Sales-Analysis-and-Forecasting/blob/main/visualizations%2FE-commerce%2FExcel%2FTotalSales%20vs.%20Country.png)


## Forecasting
- Applied SARIMAX forecasting.
![SARIMAX Forecast of Monthly Sales](https://github.com/Rehaaaan/E-commerce-Sales-Analysis-and-Forecasting/blob/main/visualizations%2FE-commerce%2FPyImages%2FSARIMAX%20Forecast%20of%20Monthly%20Sales.png)

- Applied prophet library from python
![Prophet model](https://github.com/Rehaaaan/E-commerce-Sales-Analysis-and-Forecasting/blob/main/visualizations%2FE-commerce%2FPyImages%2FSales%20Forecast%20using%20Prophet.png)

## Repository Structure
- `data/`: Raw and cleaned datasets.
- `notebook/`: Jupyter notebooks with detailed analysis.
- `reports/`: Business intelligence reports and dashboards.
- `visualizations/`: All generated visualizations.

## Conclusion
This project aimed to analyze and forecast sales data from an online retail dataset using advanced time series forecasting methods, specifically SARIMAX and Prophet. The analysis included exploratory data analysis (EDA), feature engineering, and the application of clustering techniques to understand customer segments better. Here are the detailed conclusions based on the achieved results:

### 1. Exploratory Data Analysis
- Monthly Sales Trend: The analysis revealed a clear upward trend in monthly sales, with significant seasonal variations. Peak sales periods were identified around November and December, likely due to holiday shopping.
  - Insight: This indicates the importance of holiday seasons in driving sales, with a potential strategy to focus on marketing and inventory during these periods.

### 2. Feature Engineering and Clustering

  - High-Value Customers: Represent approximately 20% of the customer base but contribute around 50% of the revenue.
  - Medium-Value Customers: Make up about 50% of the customer base and contribute roughly 35% of the revenue.
  - Low-Value Customers: Represent about 30% of the customer base but contribute only 15% of the revenue.
  - Insight: High-value customers, although a smaller segment, significantly impact revenue. Tailored marketing and retention strategies should be focused on this segment.

### 3. Forecasting

Two models, SARIMAX and Prophet, were applied to forecast future sales. The results were compared to understand their effectiveness and limitations.

#### SARIMAX Forecast

-  Performance: The SARIMAX model provided a good fit for the historical sales data, capturing both trend and seasonality effectively.
- Forecast: The model predicted an increasing trend in sales, with an expected rise of approximately 20% in the next year.
- Limitations: The model showed a sharp drop in sales at the end of the forecast period, indicating potential overfitting or the need for additional exogenous variables to improve long-term predictions.
  - Insight: While SARIMAX is effective, careful attention is needed to avoid overfitting and to ensure accurate long-term predictions.

#### Prophet Forecast

- Performance: The Prophet model captured the overall trend and seasonality, providing a reliable forecast with a similar upward trend.
- Forecast: The forecast indicated an increase in sales by about 15% over the next year, with a wider uncertainty interval compared to SARIMAX.
- Limitations: The Prophet model, while user-friendly and capable of handling missing data and outliers, can sometimes act as a black box, making it difficult to understand the underlying mechanics.
  - Insight: Prophet's ability to handle anomalies makes it robust for business applications where data irregularities are common.

Overall, the project demonstrates the utility of advanced analytics in driving strategic business decisions, with practical applications in marketing, sales planning, and customer relationship management.

## Contact
For any questions or further information, please contact:

[![**Email:**](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohammedrehan2342@gmail.com)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-rehan-483943231/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/rehah_ahan/)



