# Forex-Stock-Price-Prediction-using-Transformer


## About the Project

In recent years, deep neural networks have shown great potential in predicting stock market prices. In this report, weexplore the use of transformer-based deep neural networks for Forex stock market price prediction. We use the Transformer-XLarchitecture, which is a variant of the Transformer architecture that is designed to handle long sequences. We also use timeembeddings to encode the time information of the input data. We evaluate our model on the EUR/USD Forex pair and compare it to avariety of baseline models. Our model achieves a mean absolute error (MAE) of 0.0004 on the test set, which is a 20% improvementover the best baseline model.

![architecture](https://github.com/ZoreAnuj/Stock-formers/assets/95142805/208977e0-03d6-493d-9f46-bdf1ff96d130)

## Dataset Description and Preprocessing

The dataset we have used is that of IBM stock price history. The dataset starts from 02-16-1962 and ends on the date 31-01-2020.The data contains the Open, High, Low, Close as well as the trading Volume(OHLCV) of the IBM stock for every day between theaforementioned dates, leading to a total size of 14588 entries.


## Train, Validation and Test Split
![data_separation](https://github.com/ZoreAnuj/Stock-formers/assets/95142805/2ad03053-7f12-4690-955f-0e9bcc854b87)


## Model Architecture


## Initial Metrics and results
![initial_preds](https://github.com/ZoreAnuj/Stock-formers/assets/95142805/52fc5c8f-11f8-41a0-8883-2401a4eab0ff)
![initial_model_metrics](https://github.com/ZoreAnuj/Stock-formers/assets/95142805/35e057ab-f462-4f69-b96d-f8e544ef413a)


## Final Metrics and results

![gif](https://github.com/ZoreAnuj/Stock-formers/assets/95142805/f07d1f12-7e3e-4302-abec-d75df9c711d6)

![final_model_metrics](https://github.com/ZoreAnuj/Stock-formers/assets/95142805/7313e3fa-1312-4f4d-a0f6-f5e80b675565)


Triggering update for day: Thu Mar 27 00:45:40 UTC 2025
Triggering update for day: Sun Apr 13 03:23:16 UTC 2025
Triggering update for day: Thu Apr 17 00:47:20 UTC 2025
Triggering update for day: Thu Apr 24 00:48:26 UTC 2025
Triggering update for day: Wed May  7 01:51:37 UTC 2025
Triggering update for day: Mon May 12 01:16:58 UTC 2025
Triggering update for day: Mon Jun  2 01:18:36 UTC 2025
Triggering update for day: Fri Jul  4 01:07:23 UTC 2025
Triggering update for day: Mon Jul  7 01:22:02 UTC 2025
Triggering update for day: Wed Jul  9 01:59:05 UTC 2025
Triggering update for day: Mon Jul 28 01:27:03 UTC 2025
Triggering update for day: Tue Jul 29 01:52:16 UTC 2025
Triggering update for day: Sat Aug  2 02:11:02 UTC 2025
Triggering update for day: Mon Aug  4 01:39:30 UTC 2025
Triggering update for day: Fri Aug  8 01:13:33 UTC 2025
