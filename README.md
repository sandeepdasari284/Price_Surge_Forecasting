# Price_Surge_Forecasting


The global market is experiencing increased volatility due to economic policies, trade 
regulations, and supply chain disruptions, creating challenges for businesses, 
policymakers, and consumers in predicting and responding to price fluctuations. This study 
investigates the use of data-driven insights to predict price spikes in marketplaces impacted 
by trade regulations, tariffs, and logistical limitations. Historical pricing data, supply chain 
indices, and tariff announcement data are examined using machine learning models 
specifically Multi-Layer Perceptron (MLP) Forecasting, ARIMA, and LSTM and time
series forecasting approaches. The research develops a predictive framework that integrates 
multiple economic indicators such as inflation rates, trade policy shifts, and supply chain 
bottlenecks to provide early warnings of price volatility. The findings demonstrate that 
machine learning techniques can effectively forecast pricing surges resulting from external 
market factors, providing actionable insights for strategic decision-making in procurement, 
policy development, and consumer planning. 


**1.	Introduction:**\
The global market is becoming increasingly volatile due to economic policies, trade regulations, and supply chain disruptions. Price swings brought on by tariffs, trade restrictions, and supply chain interruptions present serious challenges for companies, decision-makers, and consumers in the modern global economy. Unpredictable price increases affect financial planning, procurement strategies, and overall market stability. Data-driven forecasting models are essential for organizations to anticipate these variations and mitigate associated risks.
The current state of research in this field shows growing interest in applying machine learning and artificial intelligence techniques to economic forecasting problems. Previous studies have explored the impact of trade policies on specific industries and commodities, but few have developed comprehensive models that account for the complex interplay of tariffs, supply chain factors, and market dynamics across multiple product categories.
This research aims to address this gap by developing a Pricing Surge Forecasting model that predicts price fluctuations resulting from these external factors, particularly focusing on the impact of tariffs and supply chain constraints on market stability. By leveraging machine learning techniques and time-series forecasting, this project seeks to develop a predictive framework that can help businesses, policymakers, and consumers proactively respond to market changes.
The principal objective is to create a prediction model that can offer early warnings of price volatility by examining historical pricing data, supply chain indices, and tariff announcement data. The findings will help businesses optimize procurement strategies, policymakers make informed trade decisions, and consumers anticipate potential cost fluctuations in essential goods and services.

**2.	Materials and Methods:**\
2.1. Data Collection and Sources\
This research leverages comprehensive datasets collected from authoritative government sources:\
•	United States Department of Agriculture (USDA): Agricultural price data, import/export statistics, and commodity market information\
•	Bureau of Labor Statistics (BLS): Producer Price Index (PPI), Consumer Price Index (CPI), and other inflation metrics\
•	Federal Reserve Economic Data (FRED): Economic indicators and market performance metrics\
•	Other government sources: Supply chain performance indices, transportation metrics, and logistics data


**The collected data includes:**
Historical prices of imported products (vegetables, dairy, meat, etc.) spanning the past 5 years.

While the dataset does not directly include tariff implementation dates or rates, these will be incorporated into the analysis through:
1.	Historical research of major tariff implementation events affecting food imports
2.	Integration of publicly available tariff announcement dates from government sources

**2.2. Model Development: **\
MLP Forecasting Approach
The core of this research is the implementation of Multi-Layer Perceptron (MLP) Forecasting, which allows for simultaneous prediction of price movements across multiple product categories. The MLP approach is particularly suitable for this problem because:
1.	It can capture non-linear relationships between input features and price movements
2.	It allows for modelling complex interactions between product categories
3.	It can incorporate both numerical and categorical features effectively
4.	It can be adapted to predict multiple time horizons simultaneously
The MLP architecture consists of:
•	Input Layer: Features derived from historical pricing data, seasonality indicators, and tariff-related factors\
•	Hidden Layers: Multiple dense layers with non-linear activation functions (ReLU)\
•	Output Layer: Predicted prices for each product category under tariff implementation scenarios

Evaluation Metrics
Model performance is evaluated using:
•	Mean Absolute Error (MAE)
•	Root Mean Square Error (RMSE)
•	Mean Absolute Percentage Error (MAPE)
•	Directional accuracy (correct prediction of price increase/decrease)
•	Category-specific performance metrics
