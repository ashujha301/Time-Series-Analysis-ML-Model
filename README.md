# Time-Series-Analysis-ML-Model
Prediction of Crude Oil prices using Machine Learning models.

Source of Data Collection: Individual Data series collected from (https://in.investing.com/) between 1 june 2000 to 1 june 2020
Data Dimensions: 
• 5001 Attributes 
• 4 Features ( Date , Gold price , Crude Oil price , Natural Gas price)

Performed EDA (Exploratory Data Analysis) on the data set 
performed Outlier Elimination. 
Used LSTM and XGboost for the comparison

*General Issues with Traditional RNN's:-*

• Suffer from short memory due to vanishing gradients they forget initial information. 

• LSTM  tackle short term memory problem. They are able to regulate flow of information.

*Overall Verdict:-*

•	XGBoost is faster than the LSTM method with equal precision in the correct tuning parameters. The drawback is its feature-importance is not so accuracy as LSTM+SHAP combination.

•	LSTM works better if we are dealing with huge amount of data and enough training data is available.

•	ARIMA requires a series of parameters (p,q,d) which must be calculated based on data, while LSTM does not require setting such parameters.

