# Google Stock Price Analysis

In our modern world, Tech Companies have rapidly grown from niche markets to providing services used by almost everyone. However, as the sector has rapidly expanded, multiple tech companies have established themselves and compete with each other. This brings up the question: How does Google, one of the largest and well known company in the sector, affected by its competitors.

In this project, we hope to compare the effectiveness of using other stocks to predict the price and using time series models. In this way, we can understand deeper about the differences of machine learning models and statistical models. 

## Notebooks
1. [Data Acquisition and Clean-up](https://github.com/Hither1/sc5010/blob/main/data.ipynb)
2. [Exploratory Data Analysis](https://github.com/Hither1/sc5010/blob/main/EDA.ipynb)
3. [Model 1: Linear Regression](https://github.com/Hither1/sc5010/blob/main/Model1.ipynb)
4. [Model 2: Tree Based Regression](https://github.com/Hither1/sc5010/blob/main/Model2.ipynb)
5. [Model 3, 4, and 5: Moving Average and Exponential Smoothing](https://github.com/Hither1/sc5010/blob/main/Model345.ipynb)
6. [Model 5: SARIMA](https://github.com/Hither1/sc5010/blob/main/Model6.ipynb)

## Problem Definition
- Are we able to predict the closing price of Google stocks using the stocks of other Information-Technology companies
- Out of all the models we used, which one "best" predicts the Google price.
## Conclusion
- All models can be used to predict Google stocks at relatively low mean-squared errors.
- Model 4 Exponential Smoothing is the best model to predict Google stocks because it has the lowest mean-squared error. 
- Model 3 Moving Average is the least suitable model among the 6 models to predict Google stocks because it has the highest mean-squared error.
## What did we learn from this project?
- Decision Tree Regression, Moving Average, Exponential Smoothing and SARIMA
- Other packages such as tqdm, itertools, statsmodels.api and warnings
- Collaborating using GitHub
## References
1. https://machinelearningmastery.com/remove-trends-seasonality-difference-transform-python/#:~:text=Differencing%20is%20a%20method%20of,structures%20like%20trends%20and%20seasonality.
2. Akaike Information Criterion https://www.scribbr.com/statistics/akaike-information-criterion/#:~:text=The%20Akaike%20information%20criterion%20(AIC,best%20fit%20for%20the%20data.
3. R. (2020, 24 juni). Cleaning Time Series Data : Time Series Talk [Video]. YouTube. https://www.youtube.com/watch?v=7_Js8h709Dw&feature=youtu.be
