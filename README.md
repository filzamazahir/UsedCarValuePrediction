# Used Car Value Prediction
A car sales service is developing an app to attract new customers where they can quickly find out the market value of their car. A machine learning model was trained to determine the current market value of the car using historical data of technical specifications, trim versions, and prices. The quality of the prediction along with the time taken to train the model and make the prediction were considered as important factors.

## To Run

1) Clone the project
```
git clone https://github.com/filzamazahir/UsedCarValuePrediction.git
```
Make sure to have pip installed, then do 
```
pip install requirements.txt
```
Run ```usedcarvalueprediction.ipynb```

## Results

After preprocessing the data and doing some exploratory data analysis, a few regression models were trained to determine the best one. Random Forest Regressor gave the lowest RMSE at 1566, it took 16 minutes to find the best parameters for the model to train it so that isn't the best choice. Random Forest Regressor, Light GBM Regressor and Catboost Regressor gave the lowest RMSE. Light GBM gave the lowest RMSE at 1606 but that was with hypertuning which took 3 minutes, whereas Catboost gave a slightly higher RMSE at 1821 but no hypertuning was done so it was done within 1.40 seconds. 
