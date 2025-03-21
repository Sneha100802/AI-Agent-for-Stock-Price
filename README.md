# Stock Sentiment Analyzer

## Project Overview
The Stock Sentiment Analyzer is an AI-powered web application that analyzes social media sentiment to predict stock prices for major tech companies. This tool combines traditional technical analysis with natural language processing to provide insights into market sentiment and potential stock movements.

## Features
- **Stock Data Analysis**: Fetches real-time and historical stock data for major tech companies using the Yahoo Finance API.
- **Technical Indicators**: Calculates and visualizes key technical indicators including:
  - Moving Averages (20-day and 50-day SMA)
  - Relative Strength Index (RSI)
  - Moving Average Convergence Divergence (MACD)
- **Social Media Sentiment Analysis**: Analyzes Twitter/social media content to gauge market sentiment toward specific companies.
- **Predictive Modeling**: Uses machine learning (Random Forest regression) to predict future stock prices based on historical data and sentiment analysis.
- **Interactive Visualizations**: Provides interactive charts and metrics for better data interpretation.

## Technologies Used
- **Python**: Primary programming language
- **Streamlit**: Web application framework for interactive dashboards
- **Pandas & NumPy**: Data manipulation and numerical operations
- **yfinance**: Yahoo Finance API wrapper for stock data retrieval
- **Scikit-learn**: Machine learning models for stock price prediction
- **Plotly**: Interactive data visualization
- **TextBlob**: Natural language processing for sentiment analysis
- **NLTK**: Additional natural language processing tools

## Project Structure
The application is organized into several core components:

1. **Stock Data Module**:
   - Fetches historical stock data
   - Calculates technical indicators
   - Provides visualization of stock performance

2. **Sentiment Analysis Module**:
   - Collects social media posts about target companies
   - Analyzes text sentiment (positive, negative, or neutral)
   - Aggregates sentiment data for correlation with stock movements

3. **Prediction Model**:
   - Prepares features from stock and sentiment data
   - Trains machine learning models for price prediction
   - Generates future price forecasts with confidence intervals

4. **Web Interface**:
   - Interactive dashboard with multiple tabs
   - Company selection and time period controls
   - Real-time visualization of analysis results

## How It Works
1. **Data Collection**: The application fetches historical stock data for the selected company and time period using the Yahoo Finance API. It also collects social media content related to the company.

2. **Technical Analysis**: The system calculates various technical indicators to identify trends and patterns in the stock price data.

3. **Sentiment Analysis**: Text from social media posts is processed to determine the overall market sentiment (positive, negative, or neutral) toward the company.

4. **Correlation Analysis**: The application calculates the correlation between sentiment scores and stock price movements to assess the impact of public opinion on stock performance.

5. **Price Prediction**: Using historical price data, technical indicators, and sentiment scores, the system trains a machine learning model to predict future stock prices.

6. **Results Visualization**: All analyses and predictions are presented through interactive charts and metrics for easy interpretation.

