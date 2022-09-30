# Crypto-Price-Movement-Prediction
## About the Project
Using various Price Prediction Models popular for trading such as Decision Trees, Random Forests and Gradient Boost Classifiers for predicting short term price movement of Cryptocurrency markets. Both classification and regression based models have been used to test the comparative efficacy of the same. The Final Step of the project will be deployment of the above model for proper backtesting and paper-testing on quantconnect to testthe existence of any alpha.

## Data and Feature Engineering
The current version of the project only uses data on BTC(Bitcoin), but will be extended to other Cryptocurrency markets as well to develop a more robust strategy. The initial OHCL data has been augmented using a variety of Popular Technical Indicators. This data set will be further augmented with Blockchain related data (data for the number of bitcoin transactions and growth of the mempool (i.e., storage of not-yet validated bitcoin transactions) etc.) as well as sentimental data from Twitter. Another idea to be tested is to directly include the data and indicators for the the past K days into the feature set of every day to better utilise the temporal relation of the Market Prices.

## The Model
The planned models to be used our Random Forests and Gradient Boost Classifiers( AdaBoost, XGBoost etc.). The current version only has the Random Forest models implemented. The hyperparameters for the model have also been tuned using sklearn's GridSearchCV.

## Performance
The currently implemented Random Forest Model achieves an accuracy of 56% over the test data, however the existence of an edge still needs to be tested taking into account the transaction fees involved for the trades being made. Proper backtesting and paper-trading over on QuantConnect will provide a better idea of the performance of the model.

## Current Targets
1. Testing the efficacy of more models over the current data to find the best model for the asset.
2. Collecting a more varied DataSet containing information about the Blockchain as well as Sentimental Analysis.
3. Improving the Feature Set to further improve performance of the models based on various Research Papers on similar topics.
4. Extending the Data to Cryptocurrency markerts besides BTC.



