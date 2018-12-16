---
title: "Torturing GPU to be Rich: Can We Predict the Price of Coin by using Machine Learning with Social Data?"
categories:
  - Coin
tags:
  - machine learning
  - cryptocurrency
  - predictive analytics
toc: true
---
*Note. This project is in work-in-progress.*

## Coworkers
- Ilhan Ryu (KAIST) & Jihoi Park (KAIST)

## Abstract
Through a variety of machine learning algorithms, this project attempts to discover and evaluate the predictive power of behavioral factors on the future price of crypto-currencies. To achieve this, we examine the impact of search frequencies, changes in policy, behavior of coin miner, big guys' twitter activities and investor’s sentiments on the macro variables of crypto-currencies. We build the Python program that automatically collects prices and corresponding aforementioned datasets from cryptocurrency exchange, StockTwits, CoinPan, Twitter, Google Trends and Naver Trends etc. Finally, we analyze the ability of each trading algorithm by conducting comprehensive performance-evaluation.

## Key Question
- Can we predict the price of coin by using machine learning with various behavioral factors?

## Why Important? & What’s New?
- The first to utilize the rich set of various behavioral factors on the future price of crypto-currencies by using machine learning

## Strategy
1. Using only the Historical Price Data
    1. ARIMA / VAR
2. The Impact of Policy & Event Changes
    1. Hard fork
    2. New exchange registration
    3. Algorithm improvements
    4. Usability in reality
    5. Air drop
    6. Rebranding
3. The Impact of Twit mentions of Big Guys
    1. Jihan Wu
    2. Roger Ver
4. The Impact of Behavior of Coin Miner
    1. Tracking Coin Hashrate
5. Predicting Kimchi Premiums
    1. Naver Trends vs. Google Trends
6. Sentiments of Coin Community
    1. CoinPan
    2. StockTwits (a microblogging platform exclusively dedicated to the financial products)

## Data
1. Coin Price / Coin Orderbook (CoinOne)
2. Community Data (StockTwits, Coinpan, Twitter)
3. Google Trends / Naver Trends
4. Coin Hashrate
5. Exchange Announcements

## Estimation Strategy
1. (Benchmark) Traditional Regression Method
2. CNN / RNN / LSTM
3. Sequence to Sequence (seq2seq) Recurrent Neural Network (RNN) for Time Series Prediction
4. Recent Algorithm: Long-term Forecasting using Tensor-Train RNNs

## Results
1. Back Testing Results for Each Strategy
2. Running Results

## Discussion
1. Additional Rooms for Alpha?
2. Additional Problems: We mainly focus on the coin price prediction. But we can extend our questions:
    1. Coin Trading Volume Prediction
    2. Coin Price Up / Down Prediction
    3. Coin Price Crash / Sudden Rise Prediction
3. Take Home Messages