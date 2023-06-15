# Impact-of-Energy-Prices-on-Inflation
Impact of Energy Prices on Inflation using Multiple Linear Regression and ARIMA

The project aims to predict the inflation of the United Kingdom in the upcoming months based on the prices of electricity, natural gas, petrol, and diesel. And also find how the change in the price of these affects the inflation of the country.

The datasets used are:

• Weekly fuel prices (pence/ litre) with the attributes price of ULSD (Ultra Low Sulphur Diesel), ULSD (Ultra Low Sulphur Petrol), Duty rate in pence/litre and VAT percentage rate. (Source: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachme nt_data/file/1119147/CSV_211122.csv/preview)

• Weekly natural gas price (GBp/Thm) interpreted from the graph from May’2013 to October’2022. (Source: https://tradingeconomics.com/commodity/uk-natural- ghttps://tradingeconomics.com/commodity/uk-natural-gas.)

• Weekly Electricity price (GBP/MWH) interpreted from the graph from May’2013 to October’2022. (Source: https://tradingeconomics.com/united-kingdom/electricity- price)

• United Kingdom Inflation Rates: 1989 to 2022 (Sources: https://www.rateinflation.com/inflation-rate/uk-historical-inflation-rate/)

## Dataset Description : 

• Dates: The dates obtained based on weekly basis in the timeframe from May’2013 to
October’2022.

• Inflation Rate: The inflation rate of United Kingdom on weekly Basis

• Electricity Price: Weekly electricity price taken in GBp/MWh (Pounds per Megawatt per
hour)

• Gas Price: Weekly natural gas price taken in GBp/thm (Pounds per Therm)

• percentChange: Change in percentage of the Gas price on a weekly basis

• change: Change in the price on the gas price on weekly basis

• Pump price in pence/litre (ULSP): Pump price of Ultra-Low sulphur petrol in pence per
litre

• Pump price in pence/litre (ULSD): Pump price of Ultra-Low sulphur Diesel in pence
per litre

• Duty rate in pence/litre (ULSP): Fuel duty rate of Ultra-Low Sulphur petrol in pence
per litre

• Duty rate in pence/litre (ULSD): Fuel duty rate of Ultra-Low Sulphur Diesel in pence
per litre

• VAT percentage rate (ULSP): Value added tax percentage of the petrol price

• VAT percentage rate (ULSD): Value added tax percentage of the Diesel
price

## Modelling :

After properly understanding the dataset now the further step is to find the perfect model to predict the dependent factor which is the Inflation rate in our case. The dataset follows a linear trend so, I have decided to use multiple linear regression and Time series to predict the Inflation rate.

## Results : 

In order to find the trends of the analysed data over a while I've used Time series modelling and found a good correspondence of all the independent variables to the Inflation rate. For predicting and forecasting the Inflation rate with the help of historical data I've used ARIMA modelling. I was able to predict the Inflation rate from January 2022 to May 2023 using the model.

