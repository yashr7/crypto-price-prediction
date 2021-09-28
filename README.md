# DMA course project - Team 07
# Cryptocurrency Closing Price Prediction Challenge 


## 1. Problem Statement

> After the boom and bust of cryptocurrencies’ prices in recent years, cryptocurrencies have been increasingly regarded as an investment asset. Because of their highly volatile nature, there is a need for good predictions on which to base investment decisions. Different existing studies have leveraged machine learning for more accurate cryptocurrency price prediction. We are interested in applying different modeling techniques to samples with different data structures (qualitative and quantitative data) and dimensional features to achieve an optimization in price prediction.


## 2. Data

[Dataset from Zindi](https://zindi.africa/competitions/cryptocurrency-closing-price-prediction/data), 

There are 3 datasets:
1. **Train.csv** - contains the target. This is the dataset that you will use to train your model..
2. **Test.csv** - resembles Train.csv but without the target-related columns. This is the dataset on which you will apply your model to..
3. **SampleSubmission.csv** - shows the submission format for this competition, with the ‘id’ column mirroring that of Test.csv and the close column containing your predictions.

## 3. Evaluation

For this problem, our main goal is to reach and exceed a given threshold (a specified RMSE score) in the final developed model.

To see how well our model is doing, we'll calculate the RMSE and then compare our results to others on the [Zindi leaderboard](https://zindi.africa/competitions/cryptocurrency-closing-price-prediction/leaderboard).

## 4. Features

For this dataset, Zindi provided a [data dictionary](https://zindi.africa/competitions/cryptocurrency-closing-price-prediction/data)  which contains information about what each attribute of the dataset means. 

The target value is the closing price. We have data extracted in an interval of 1h for a period of one year (from 1st of March 2020 to 1st of March 2021).
