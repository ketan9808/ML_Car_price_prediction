# Car Price Predictioin

Predict price of pre-owned cars using Machine Learning.

## Introduction

This project is inspired by a kaggle dataset called as [Used cars database](https://www.kaggle.com/orgesleka/used-cars-database#autos.csv). The aim is to predict the price of the used cars based on condition of car. The condition of cars are presented in CSV format. Also the content of the dataset is in german and are needed to be converted to English. In detailed explanation of preprocessing is given in the code in form of comments.
The models are created on two variety of dataset one with missing value removed and other with missing value imputed with appropriate value.For modelling purpose I've created first baseline model the Linear Regression model and then finally Random Forest Regressor model.

## Getting Started

As always to work on/alter the code, clone the repository and you are ready to go provided you have installed the required library(see requirements.txt). If you don't have them just intall them by using the following command

```
pip install -r requirements.txt #to be uploaded soon
```

or you can open the notebook using Google colab(link to be uploaded soon)

## Built With

* [pandas](https://pandas.pydata.org/) - Python Data analysis library
* [seaborn](https://seaborn.pydata.org/) - The graph plotting library
* [sklearn](https://scikit-learn.org/stable/) - The Machine Learning framework used

## Used case

The created model can be hosted and used along with a mobile app or web app to calculate the price of preowned cars. also the condition of the vehicle can be extimated using different computer vision technique and can be fed to model directly for price prediction.

## License

This project is licensed under the GNU General Public Licence v3.0 License - see the [LICENSE.md](LICENSE.md) file for details.