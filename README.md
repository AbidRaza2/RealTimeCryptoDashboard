# RealTimeCryptoDashboard
A real time dashboard for cryptocurrency data where its trends and trends prediction can be analysed.

1. **Introduction** 
Cryptocurrencies represent a rapidly evolving asset class characterized by high volatility and 24/7 
trading activity. Real-time analytics and predictive modeling are crucial for both individual traders and 
institutional investors to gain insights and make informed decisions. This project presents a real-time 
cryptocurrency analytics dashboard developed using Dash, with data processing and machine learning 
capabilities powered by Apache Spark and PySpark MLlib.

3. **Objectives** 
 Collect and visualize real-time cryptocurrency price data. 
 Perform real-time data processing using Spark. 
 Build and integrate predictive models for trend classification. 
 Enable interactive exploration of historical and current trends via a web-based dashboard.

4. **Tools and Technologies**
 Dash (Plotly) - Web-based dashboard interface 
 SQLite - Lightweight local database for data storage 
 Apache Spark (PySpark) - Distributed data processing 
 MLlib - Spark's machine learning library for classification 
 Python - Core language used throughout the project 
 Google Colab - Development environment for hosting the project

5. **System Architecture** 
**Components:** 
 Data Collection: Cryptocurrency price data is fetched using a public API and inserted into an SQLite 
database at regular intervals. 
 Data Storage: Prices along with timestamps are stored persistently in SQLite. 
 Data Processing: Spark ingests data from SQLite and performs ETL operations. 
 Machine Learning Models: Trend Classification using Random Forest.  
 Visualization: Real-time graphs, historical trends, and ML outputs

6. **Features Implemented** 
 Real-Time Data Handling 
 Real-Time Graphs 
 Machine Learning Integration 
 Interactive Dashboard (Tabs: Overview, Trend, Prediction, Database View)

7. **Machine Learning Models** 
Price Trend Classification: 
 Input: current_price, previous_price 
 Feature: Price difference 
 Label: 1 (uptrend), 0 (downtrend) 
 Model: RandomForestClassifier

8. **Future Work** 
 Add filtering options by date/time range 
 Implement anomaly detection 
 Extend models using LSTM 
 Deploy with backend support (PostgreSQL + Docker)
 
9. **Conclusion** 
This project demonstrates the integration of real-time data ingestion, processing, and machine learning within 
a user-friendly dashboard. By leveraging Apache Spark and Dash, the system provides a powerful framework 
for cryptocurrency analytics.

10. **References** 
 Apache Spark Documentation: https://spark.apache.org/docs/latest/ 
 Plotly Dash: https://dash.plotly.com/ 
 CoinGecko API: https://www.coingecko.com/en/api 
 SQLite Documentation: https://sqlite.org/docs.html 
