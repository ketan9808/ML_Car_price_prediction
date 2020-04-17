# ML_Car_price_prediction
Predict price of pre-owned cars using Machine Learning.

This notebook (Car_price_prediction.ipynb) demonstrate how to predict the price of pre-owned cars using different Machine Learning Techniques.The Dataset was taken from kaggle and contain some words from foregin language(Need to convert them to English). I have used Pandas Dataframe to store and process the data and seaborn for visualization purpose. For modelling Machine Learning model I have used Linear regression and Random forest regressor for prediction. I have also create baseline model to check the baseline accuracy and loss.

The data contain a lot of outliers so in the first part I have visualized them then cleaned them and then visualized them again. Also some columns are not contributing in predicting the final result and I have dropped them.

The data contain a lot of missing data so I have created 2 dataset one with Missing value omitted and other with missing value imputed and then created baseline, Linear Regression, Random forest regressor model for both of them.


link to [dataset](https://www.kaggle.com/orgesleka/used-cars-database#autos.csv)