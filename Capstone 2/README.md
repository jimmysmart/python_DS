### Gulf Coast Area Rainfall Prediction
Files include:
Python Jupyter Notebook: contains the full code and visualizations for data cleaning, wrangling, analysis, visualization, and predictive modeling.
Slide Deck: Presentation of the project in powerpoint form
Our data is from https://ww.ncdc.noaa.gov/ and consists of 5 different datasets from each of our 5 chosen cities along the Gulf Coast. Collected between January 2010 through December 2019. Each dataset consists of daily weather data and is saved as a CSV file

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
### Conclusion
#### Summary
Through our data wrangling efforts and visualizations we were able to see weather trends than can be usual to serve any clients looking to see how weather has been and may be in the future.
When looking at temperatures over the past decade we were able to see that there has been an upward trend towards average temperatures rising each year. A degree hotter might not seem like much but the overall story can show devastating results if proper precautions aren’t met. Farmers may need to adjust their watering and feeding habits to make sure their crops and/or animals can adapt to rising temperatures. 
As for rainfall, we were able to see trends over the past decade. For the most part, the area hasn’t had to deal with any long lasting droughts. Being able to have a visual of upcoming trends can help various industries to adjust their habits based on the time of year and expected rainfall or non rainfall.
