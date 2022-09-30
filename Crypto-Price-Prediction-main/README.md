# Crypto-Price-Movement-Prediction
## About the Project
Using several price prediction models, including as Gradient Boost Classifiers, Random Forests, and Decision Trees, which are used in trading, to forecast short-term price movement of cryptocurrency markets The relative effectiveness of the same has been tested using both classification-based and regression-based models. The implementation of the aforementioned model for appropriate backtesting and paper-testing on QuantConnect to verify the presence of any alpha will be the project's last step.

## Data and Feature Engineering
The project will be expanded to include data from other cryptocurrency marketplaces in addition to BTC (Bitcoin) in order to create a more effective approach. A number of Popular Technical Indicators have been used to supplement the primary OHCL data. This data set will also be supplemented with emotive data from Twitter and Blockchain-related data, such as information on the volume of Bitcoin transactions and the expansion of the mempool (i.e., storage of unconfirmed Bitcoin transactions). To better use the temporal relationship of the Market Prices, another proposal that will be investigated is to directly add the data and indications for the previous K days into the feature set of every day.

## The Model
Gradient Boost Classifiers and Random Forests are the intended models to be employed ( AdaBoost, XGBoost etc.). Only the Random Forest models are used in the present edition. Additionally, the model's hyperparameters have been adjusted using sklearn's GridSearchCV.

## Performance
The currently used Random Forest Model obtains a 56% accuracy over the test data, but it is still necessary to verify whether there is an advantage when taking into consideration the transaction costs associated with the trades being performed. An accurate backtesting and paper trading on QuantConnect will give a better picture of the model's performance.

## Current Targets
1. Testing the efficacy of more models over the current data to find the best model for the asset.
2. Collecting a more varied DataSet containing information about the Blockchain as well as Sentimental Analysis.
3. Improving the Feature Set to further improve performance of the models based on various Research Papers on similar topics.
4. Extending the Data to Cryptocurrency markerts besides BTC.



