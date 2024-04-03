# TATA-Motors-Closing-Price-Forecasting-with-ARIMA-SARIMA-SARIMAX
Forecasting 30 days price trend or possible movement in Tata Motor
## Analysis and Findings 

## Adjusted colsing price define 
<img align="center" alt="dataanalysis"  width = "1000" height = "350px" src="Screenshot 2023-12-10 093226.png">

1. Maximum price range has been identified in the preiod of 2016
2. Drustic fall in stock price has been noticed after 2017 till to 2020
3. Leadership of Tata group movement toward electric car model boost stock price in 2021 that impact positive in price at 
   (all time hige) ATH around 650

<img align="center" alt="dataanalysis"  width = "1000" height = "350px" src="Screenshot 2023-12-10 093444.png">

<img align="center" alt="dataanalysis"  width = "1000" height = "350px" src="Screenshot 2023-12-10 093804.png">
  

## Insights and findings 
1. 50 Days Moving average indicate cross-over of moving avergae line has potentiality of rise in price 
2. Cross-down of 50 Days moving avergae line represent high potentiality of fall in stock price
3. 154 days moving avergae indicate short term trend of stock price that could e use for short trem investment 
4. Cross-down of 15 MA in year 2017 indicate huge fall in stock price till 2020                                                                 .
5. whereas Cross-over of 50 MA in 2022 indiacte growth of stock price around to 600.
6. It is defing short term investmnet plan esatblishment 15 Days MA is effective 
7. 50 Days MA need to be consiosder for long term investment.

<img align="center" alt="dataanalysis"  width = "1000" height = "350px" src="Screenshot 2023-12-10 094251.png">
  
## Insights and findings (Exponential Moving Average)
1. 50 EMA volume indicate possible movement of stock price whereas excess hike volume impact positive on stock price
2. 200 EMA volume indiacte long term possibility regarding stock price movement
3. Additional imformation comes out huge growth in volume FY 2021 sustain as positive movement of Tata Motors
4. Middle range volume like (0.3 to 0.5) indiacte consolidation of stock price betweem specific price range.
5. 50 EMA lime above 200 MA indicate positive movement in stock price 
6. 50 EMA lime below 200 MA indicate negative movement in stock price

## Stationarity check
Chceking data is stationary or not by adfullaer test
### Result 
ADF statistics: 0.079361
p-value: 0.964623
Fail to reject null hypothesis. Data is not stationary

## lets define 
p = 1
q = 1
d = 1

## Forecast close price trend by ARIMA 

<img align="center" alt="dataanalysis"  width = "1000" height = "350px" src="Screenshot 2023-12-10 094845.png">

## Forecast close price trend by SARIMAX 

<img align="center" alt="dataanalysis"  width = "1000" height = "350px" src="Screenshot 2023-12-10 094927.png">


