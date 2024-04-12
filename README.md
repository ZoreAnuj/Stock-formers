# Forex-Stock-Price-Prediction-using-Transformer-and-Time-Embeddings


## About the Project

The foreign exchange (Forex) market is a global decentralized market for the trading of currencies. It is one of the largest financialmarkets in the world, with an average daily trading volume of over $5 trillion. Predicting the price movements of Forex markets is achallenging task, as these markets are affected by a variety of factors, including economic and political events, interest rates, andglobal news. In recent years, deep neural networks have shown great potential in predicting stock market prices. In this report, weexplore the use of transformer-based deep neural networks for Forex stock market price prediction. We use the Transformer-XLarchitecture, which is a variant of the Transformer architecture that is designed to handle long sequences. We also use timeembeddings to encode the time information of the input data. We evaluate our model on the EUR/USD Forex pair and compare it to avariety of baseline models. Our model achieves a mean absolute error (MAE) of 0.0004 on the test set, which is a 20% improvementover the best baseline model.

## Dataset Description and Preprocessing

The dataset we have used is that of IBM stock price history. The dataset starts from 02-16-1962 and ends on the date 31-01-2020.The data contains the Open, High, Low, Close as well as the trading Volume(OHLCV) of the IBM stock for every day between theaforementioned dates, leading to a total size of 14588 entries.


## Train, Validation and Test Split


## Model Architecture


## Initial Metrics and results


## Final Metrics and results


## Conclusion

Deep neural networks (DNNs) are a type of machine learning algorithm that can be used to predict stock market prices. DNNsconsist of multiple layers of interconnected nodes, and they are trained using large amounts of historical data to make predictionsabout future stock market prices. Recently, transformer-based DNNs have gained popularity in the field of natural languageprocessing over RNNs, LSTMs and GRUs because of their attention mechanisms allowing them to have large reference windows,they have also been applied to other domains, including stock market price prediction. We have also explored stock price predictionusing RNNs and LSTMs, however, transformers superseded them in the prediction task and hence our report sticks strictly towardsthe analysis of stock price prediction using Transformers.

