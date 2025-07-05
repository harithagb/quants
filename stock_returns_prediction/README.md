# Stock Price Movement Forecasting

## Project Title  
Forecasting Stock Price Movement Using News Sentiment and Technical Indicators

## Overview  
This project combines sentiment analysis of financial news headlines with technical indicators to predict short-term stock price movements. A Random Forest classifier is trained on engineered features from both domains.

## Key Techniques  
- Sentiment analysis (VADER, TF-IDF on headlines)
- Technical indicators (moving averages, RSI, returns)
- Feature engineering and merging
- Random Forest classification and evaluation

## How to Run  
1. Collect historical price and headline data in the working directory.
2. Open `Final_project_StockPrediction.ipynb`.
3. Ensure required libraries are installed: `nltk`, `sklearn`, `pandas`.
4. Run cells sequentially to build the pipeline and evaluate performance.

## Possible Extensions  
- Integrate FinBERT or other transformer-based sentiment models
- Use LSTM or Temporal CNNs for sequential modeling
- Build real-time monitoring or alert system using APIs
