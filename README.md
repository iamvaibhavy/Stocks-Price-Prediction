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

**Pre-processing the datasets and transform the data into a tabular format**
![Pre-Processing](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/a8650593-7829-47d3-ba30-cab54df26130)

**Graph Between Date Vs Open Price**
![Processed_Graph](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/9e5cf825-e8ca-4d27-bc45-bd2772b9fc73)

**Apply LSTM deep learning, run each dataset through multiple epochs, and perform testing analysis with graphical representation**
![D1](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/7fff5d83-97d0-4cb0-8e10-a0f432bf027a)
![D2](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/56b06411-11df-44fa-955c-10cb579bcea7)
![Deep Learning_TestingResult ](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/4e55f167-6f8d-4d0c-abbc-8583fcd6e0d0)


**Utilize a regression model (Random Forest Regression) to predict the accuracy of the models and forecast stock prices**
![r1](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/b29dfcb4-bf41-4bab-a1e7-f2ba3b2c5500)
![r2](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/84c4bf08-11c0-4b29-b9df-af5bc1c9b6cf)
![r3](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/2cb3acef-60b6-4eb4-a4bd-3ec8ed0722b2)
![r4](https://github.com/iamvaibhavy/Stocks-Price-Prediction1/assets/97886453/2f2f6db4-1d38-4805-8132-eac5b1dd7b08)




### Future Avenues:

Future enhancements for this project include incorporating additional parameters, such as financial ratios and multiple instances, to enhance accuracy. The algorithms can also be adapted to analyze public comments, identifying patterns and relationships between customers and corporate employees. Additionally, traditional algorithms and data mining techniques can also be employed to predict the overall performance structure of the corporation.
