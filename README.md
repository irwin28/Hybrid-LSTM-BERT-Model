# Stock Price Prediction Using LSTM-BERT Model

This repository contains the source code and data for the research project focused on predicting stock prices on the Bursa Malaysia using a hybrid model that integrates Long Short-Term Memory (LSTM) neural networks with Bidirectional Encoder Representations from Transformers (BERT) for sentiment analysis. The model is designed to leverage both historical stock data and news article sentiment to enhance prediction accuracy.

## Project Overview

Accurately predicting stock prices is a complex challenge due to the dynamic and multifaceted nature of financial markets. This research proposes a hybrid model combining LSTM for time-series analysis of stock prices and BERT for sentiment analysis of news articles. The integration of these two models aims to capture both the temporal dependencies of stock price movements and the influence of market sentiment on stock performance.

Despite promising outcomes, several limitations exist:
- The reliance on historical data may not fully reflect the real-time dynamics of the stock market.
- External economic events and global crises are not accounted for in the dataset.
- Neutral sentiments and data anomalies can affect the accuracy of sentiment analysis.
- Data scraping from news sources like The Star introduced noise that impacted model predictions.

However, this research lays a solid foundation for future advancements in stock price prediction and sentiment analysis.

## Features

- **LSTM Model**: Used for time-series forecasting of stock prices.
- **BERT Model**: Applied for sentiment analysis on news articles related to stock market movements.
- **Hybrid Approach**: Combines the strengths of both LSTM and BERT for more accurate predictions.
- **Business Intelligence (BI) Tools**: Integrated to visualize model performance and enhance decision-making.

## Dataset

The project utilizes two main datasets:
1. **Historical Stock Data**: Collected from the Bursa Malaysia stock market.
2. **News Articles**: Scraped from The Star to analyze market sentiment through BERT.

## Requirements

To run this project, you'll need the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `tensorflow`
- `transformers`
- `matplotlib`
- `seaborn`

You can install the required dependencies using:

```bash
pip install -r requirements.txt
