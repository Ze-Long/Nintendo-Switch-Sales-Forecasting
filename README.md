## Nintendo-Switch-Sales-Forecasting

![alt tag](https://github.com/Ze-Long/Ze-Long.github.io/blob/master/images/switch.png)

The Nintendo Switch is a video game console developed by Nintendo, released worldwide in most regions on March 3, 2017. In this case competition, I was tasked to forecast the US sales of Nintendo Switch in the first week in May.

The following code is run through Jupyter Notebook. I work with Scikit-Learn, the machine learning framework, to build different regression models to predict the sales amount of Nintendo Switch and evaluate them with cross validation.

## Algorithms Used
Random Forest

LightGBM

Extreme Gradient Boosting

Multilayer Perceptron
  
Long Short-Term Memory
  
## Model Performance

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/RandomForest.png)

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/XGBoost.png)

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/MLP2.png)

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/LSTM2.png)

## Final Prediction

These 4 models achieve similar performance so I choose to combine them together. I calculated the reciprocals of their MAEs and normalized them in order to give the models their weights respectively. The final prediction is the weighted sum of their prediction, which is 

