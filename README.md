# Forecasting Rental Prices
Py Nb to predict rental prices in Australia's neighbourhoods.

Scope:¶
- Evaluate the time series evolution of property rentals in my neighbourhood (Kensington, PC 5068).
- Use this information to create a model that will forecast future rental prices.

Data source: https://data.sa.gov.au/data/dataset/private-rent-report

### Stages of analysis
1. Research about propery prices and rental prices evolution in Adelaide and other Australian capitals.
2. Exploring available data and choosing an appropiate source.
3. Exploring data selected and pre-processing
4. Visualizing data and extracting insights without jumping into conclussions.
5. Numerical analysis of the information.
6. Selecting model: ARMA.
7. Implementing Box-Jenkins methodology to selecting a suitable model.

    7.1. Identification of the data and analysising model assumptions such as stationarity.
    
    7.2. Use of visual assistance to analysie the data distribution and its decomposition.
    
    7.3. Estimation of best models in terms of pre-defined selection criteria.
    
    7.4. Selecting the best model according to criteria.
    
    7.5. Exploring how auto arima algortithm would decide on a model.
    
    7.6. Fitting the model and running visual and analytical diagnostics on it (including plot diagnoticts and statistical tests results on model assumptions)
    
    7.7. Splitting the data into training and testis data to evaluate the accuracy of the model while reducing overfitting. Parameters evaluated: MSE and RMSE.
    
    7.8. Production: Fitting the model with all available data and analysing its predictions.
    
    7.9. Using the model to forecast rental prices over the next 3 years.
    
8. Improving accuracy suggestions: More data, exploring model response to exogenous and correlated variables and exploring the impact of government and financial institutions policy changes.
