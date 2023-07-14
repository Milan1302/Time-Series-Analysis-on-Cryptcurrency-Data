# Time-Series-Analysis-on-Cryptcurrency-Data
Our algorithm seeks to use historical prices and the sentiment of Wikipedia edits to forecast the trends in the price of cryptocurrencies. For this forecasting, I have implemented Random Forest, XG Boost Algorithms, and LSTM.
The sentiments of the Wikipedia Edits were found using the file sentiment analysis. The dataset of 'Wikipedia edits' in the dataset folder is generated using the same.
The file 'RandomForest' predicts the increase or decrease in data using the analyzed sentiments and the closing price. The algorithms used here are Random Forest Classifier and XG Boost Classifier.
The file 'LSTM' predicts the increase or decrease in data using the closing price. The algorithm used here is LSTM.
