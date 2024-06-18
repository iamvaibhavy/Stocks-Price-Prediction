# Stocks-Price-Prediction

Deep learning project was undertaken where an LSTM-based model and a ML regression model were trained to predict any stock prices. The predicted prices from both models were then compared with the actual values to evaluate their performance.

### About the Project:

Accurate stock prediction can yield substantial profits for sellers and brokers. It is frequently argued that stock market behavior is chaotic rather than random, indicating that predictive insights can be derived from thorough historical data analysis. Machine learning has proven to be an effective tool for modeling these processes, offering predictions that closely match actual market values, thereby enhancing accuracy. The utilization of machine learning in stock prediction has attracted significant attention due to its precision and effectiveness.

The most crucial aspect of machine learning is the dataset utilized; it must be as accurate and comprehensive as possible, as even minor variations can significantly impact outcomes. In this project, supervised machine learning is applied to a dataset obtained from NSE Historical Dataset (i.e. TATA-Chemicals-Limited). The dataset includes variables such as Date, Open, High, Low, Last, Close, Total Trade Quantity, and Turnover (Cr). The Open, Close, Low, and High variables represent different bid prices for the stock at various times.

The model is evaluated using a separate test dataset. Both Regression and LSTM models are utilized for prediction. Regression focuses on minimizing error, while LSTM is adept at capturing long-term data dependencies. The project involves plotting graphs to visualize price fluctuations over time for comparing actual and predicted prices for the LSTM model. Additionally, the project estimates the accuracy percentage and predicts sample prices.

## Getting Started
1. Download or clone project from github
2. Run project

#### Model Analysis

**Pre-Processing the dataset and obtain the data into the table form**
![Pre-Processing](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/a8650593-7829-47d3-ba30-cab54df26130)

**Graph Between Date Vs Open Price**
![Processed_Graph](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/9e5cf825-e8ca-4d27-bc45-bd2772b9fc73)

**Applying LSTM Deep learning and Run every dataset through Epochs**
**Testing Analysis Graph**
![Deep Learning_TestingResult ](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/cee71ab4-79b3-48b1-9f0c-e7aba37ae615)


### Future Avenues:

Future enhancements for this project include incorporating additional parameters, such as financial ratios and multiple instances, to enhance accuracy. The algorithms can also be adapted to analyze public comments, identifying patterns and relationships between customers and corporate employees. Additionally, traditional algorithms and data mining techniques can also be employed to predict the overall performance structure of the corporation.
