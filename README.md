# car-price-model
a linear regression model to predict car prices

This small project is based on chapter 2 "Machine learning" for regression" of Alexey Grigorevs book "Machine Learning Bookcamp" and uses kaggle's car dataset (https://www.kaggle.com/CooperUnion/cardataset).

On 2020-08-17, I used scikit learn to train the model. The notebook is uploaded and has the filename 200817-car-scikit.ipynb

## Additional simple linear regression model

- I also added one simple linear regression model built with scikit-learn for the prediction of salaries based on the years of experience taken from the course "Machine Learning A-Z" (Udemy))
- the model can be found here in this repository: 201027-LinearRegression-Salaries.ipynb

## Additional support vector regression (SVR) model

- I also added one SVR model built with scikit-learn for the prediction of salaries based on the years of experience taken from the course "Machine Learning A-Z" (Udemy))
- the model can be found here in this repository: 201102-SVR-Salaries.ipynb
- the simple linear regression model and the SVR model are trained on the same dataset, but performance is different (the SVR does not correctly predict the salary for the postion level 10). 


## Additional multiple linear regression model

- I also added one multiple linear regression model built with scikit-learn for the prediction of startup profits based on multiple feature variables taken from the course "Machine Learning A-Z" (Udemy))
- the model can be found here in this repository: 201030-MultLinReg-Startups.ipynb
- the dataset can be found here in this repository: 50_Startups.csv

## Additional decision tree regression model

- I also added one decision tree regression model built with scikit-learn for the prediction of the car prices based on multiple feature variables
- the model can be found here in this repository: 201111-DecTreeReg-CarPrice-Clean.ipynb
- the dataset can be found here in this repository: car_price_data.csv
- the rmse is much lower than of the model in this notebook: 200817-car-scikit.ipynb
- it would be interesting to check whether that is due to the different model type or due to the more carfully applied missing value imputing methods


