# 📊 Banking Dashboard using Power BI

This repository showcases an interactive and insightful banking dashboard built using Microsoft Power BI. The project is centered on analyzing client-bank relationships, loan and deposit data, and client engagement patterns based on a structured multi-table dataset.

## 📁 Dataset Overview

The dataset includes multiple interrelated tables:
- **Banking Relationship**
- **Client-Banking**
- **Gender**
- **Investment Advisor**
- **Period**

These are connected through primary and foreign keys to enable seamless data modeling and cross-table analysis.

## 🛠️ Data Cleaning and Transformation

To enhance analysis and visualization, several transformations and calculated fields were created:

- **Engagement Timeframe**: Shows the duration of client engagement with the bank.
- **Engagement Days**: Calculated using `DATEDIFF` to represent total days a client spent with the bank.
- **Income Band**: Categorizes clients based on estimated income (e.g., Low < 100,000, Mid < 300,000).
- **Processing Fees**: Derived based on the fee structure using a conditional formula (`SWITCH`).
  
Power BI DAX functions such as `SUM`, `SUMX`, `DISTINCTCOUNT`, and `SWITCH` were used to compute key performance indicators.

## 📈 Dashboard Features

The Power BI report includes the following pages:

- **Home Page**: Summary of key metrics and navigation.
- **Loan Analysis**: Deep dive into loan distribution and trends.
- **Deposit Analysis**: Visualization of deposit patterns and client contributions.
- **Summary Dashboard**: Consolidated view of overall bank and client performance.

## 🚀 Future Enhancements

This dashboard can be further improved by:
- Integrating real-time data for live monitoring.
- Adding filters for user-driven insights.
- Including visual cues for risk profiles or account types.

## 📌 Conclusion

This Power BI dashboard provides a clear, visual way to understand customer behavior, identify trends, and support strategic decision-making in the banking domain.

---
