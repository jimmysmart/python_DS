### Gulf Coast Area Rainfall Prediction
Files include:
Python Jupyter Notebook: contains the full code and visualizations for data cleaning, wrangling, analysis, visualization, and predictive modeling.
Slide Deck: Presentation of the project in powerpoint form
Our data is from https://ww.ncdc.noaa.gov/ and consists of 5 different datasets from each of our 5 chosen cities along the Gulf Coast. Collected between January 2010 through December 2019. Each dataset consists of daily weather data and is saved as a CSV file

### Capstone Navigation
Notebooks - https://github.com/jimmysmart/python_DS/tree/master/Capstone%202/notebook

Final Reports - https://github.com/jimmysmart/python_DS/tree/master/Capstone%202/reports

#### Primary Goal
History is known to repeat itself at times but predicting if/when history will repeat itself is an ongoing issue. The best approach is look for patterns of the past while comparing it to patterns of the present. The goal of this project is: Can we predict rainfall for the Gulf Coast area?

look at days that had rainfall amounts
look at days that didn't have rainfall amounts.

### Data Cleaning & EDA
#### Objectives
Our 5 datasets were given a quick cleaning within their original Excel format before being saved as CSV files and read into our notebook as one through glob. Concat was used to create one dataframe. Find any missing/null values and respond to them accordingly. I created a new timeseries columns before using various data visulization techniques to look at our data.
### Predictive Modeling
##### Objectives
I will first need to collect of the the features to be modeled into one dataframe. After this, some feature engineering is done to add month, day, and time columns, as well as convert categorical varibles to dummy variables. Since rainfall is our targeted variable, it was removed.


name (without outliers) R2 - Test R2 - Train MAE - Test MAE - Train RMSE - Test RSME - Train

FB Prophet -0.001 NaN 0.248 NaN 0.468 NaN

Linear Regression(multiple) 0.223 -2.600 0.214 0.220 0.396 0.406

XGBoost 0.255 0.650 0.161 0.220 0.373 0.217

Random Forest 0.292 0.847 0.167 0.065 0.382 0.142



### Conclusion
Our machine learning efforts culminated in a regression analysis on rainfall for the Gulf Coast Area. Our models had a hard time pinning down exactly how much rainfall will occur. The features we used did not have as signifanct of an influence towards our dependent variables as we thought it would. More features may be needed as well as more data points. Future hyperparameter tuning may help as well as our XGBoost and Random Forest models showed us enough that further modeling may be able to help predict rainfall better. We were ble to see some interesting trends over the past decade that will be useful to any clients who depend on historical and future trends to better utilize their company's services.
