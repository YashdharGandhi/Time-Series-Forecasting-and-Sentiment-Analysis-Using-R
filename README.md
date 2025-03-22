# Time Series Forecasting and Sentiment Analysis Using R

## Overview
This project explores two key domains: **Time Series Forecasting** and **Sentiment Analysis** using R.  
- **Time Series Forecasting:** We analyze **Personal Consumption Expenditures (PCE)** data and compare three forecasting models: **ARIMA, ETS, and Drift.** The goal is to determine the most effective model based on error metrics such as RMSE and MAE.
- **Sentiment Analysis:** We perform **Topic Modeling** on hotel reviews, categorizing them into positive and negative sentiments. We use **Latent Dirichlet Allocation (LDA)** to identify key topics influencing customer satisfaction and dissatisfaction.

## Data Description
The project utilizes the following datasets:
1. **PCE.csv** - Contains Personal Consumption Expenditures (PCE) data with time-series values.
2. **HotelsData.csv** - Includes hotel customer reviews with review text and ratings.

## Tasks
### 1. Time Series Forecasting (PCE Data)
- Handle missing values using **spline interpolation**.
- Convert date format for time-series analysis.
- Train **ARIMA, ETS, and Drift models**.
- Compare models using **RMSE & MAE**.
- Forecast **PCE for October 2024**.

### 2. Sentiment Analysis (Hotel Reviews)
- Clean and preprocess review text (tokenization, stopword removal, lemmatization).
- Separate **positive and negative** reviews.
- Apply **LDA topic modeling** to extract key themes.
- Visualize **word clouds** and **topic distributions**.

## Key Findings
- **ARIMA** outperforms ETS and Drift in forecasting PCE, achieving the lowest RMSE and MAE.
- **Positive reviews** focus on **room quality, location, and overall experience**.
- **Negative reviews** highlight issues with **check-in processes, payment, and room facilities**.

## Requirements to Run
To execute this project, ensure you have the following **R libraries** installed:

install.packages(c('dplyr', 'tidyr', 'stats', 'forecast', 'ggplot2', 'imputeTS', 'tidytext', 
                   'tm', 'topicmodels', 'tokenizers', 'SnowballC', 'textstem', 'LDAvis', 
                   'servr', 'ldatuning', 'wordcloud'))
## Author
**Yashdhar Gandhi**

##License
This project is licensed under the MIT License.
