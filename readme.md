# Project 2

Our project consist in two main parts:

1. Employ machine learning classification algorithms for stock price returns. Classify the return as 1 if it's positive or 0 if it’s negative. We want to employ time series features (closing prices and volume) combined with sentiment analysis
2. Algorithmic trading. We want to implement an AT tool  employing results from step 1.




Features in machine learning: 
 * Stock price movement
- Stock volume movement
- Treasury bonds price movement 
- Treasury bonds volume movement (derive from TLT, a very liquid ETF on 20Y treasuries)
- Sentiment analysis on the stock we want to classify. We will build a time series of the index derived from the VADER library.


Data (and sources):
- Stocknewsapi (https://stocknewsapi.com/)
- Alpaca


Algorithms we want to explore for classification:
- K-nearest neighbors
- LSTM
- SVM
- Random Forest


