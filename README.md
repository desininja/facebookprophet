# facebookprophet
Predicting the future prices of Avocado using Facebook prophet.

Prophet is an open source tool used for time series forecasting.


- You must install fbprophet package as follows: 
     pip install fbprophet
- If you encounter an error, try: 
    conda install -c conda-forge fbprophet
    
    
## Understanding the intuition behind facebook prophet:
- Prophet is an open source software released by Facebook's core Data Science team.
- Prophet is a procedure for forecasting time series data based on an additive model where non-linear treends are fit with yearly, weekly, and daily seasonality, plus holiday effects.
- Prophet works best with time series that have strong seasonal effects and several seasons of historical data.
- For more information, please check this out:
    - https://www.analyticsvidhya.com/blog/2018/05/generate-accurate-forecasts-facebook-prophet-python-r/
    - https://facebook.github.io/prophet/docs/quick_start
- Prophet implements an additive regression model with four elements:
    - A piecewise linear, Prophet automatically picks up change points in the data and identifies any change in trnds.
    - A yearly seasonal component modeled using Fourier series.
    - A weekly seasonal component.
    - A holiday list that can be manually provided.

# Facebook Prophet Features

* Accurate and Fast
  - Facebook teams uses Prophet for accurate forecasting and planning.
  - Prophet can generate results in seconds.
* Automatic
  - No need to perform data preprocessing.
  - Prophet works with missing data with several outliers.
* Domain knowledge integration
  - users can tweakforecast by manually adding domain specific knowledge.
  
### A few model specification during training:

The data should consist of only two columns one date column named as "ds" and other the target column named as "y".
