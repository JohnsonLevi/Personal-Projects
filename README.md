# Time-Series-Econnometrics-FinalProject
Hello, this is my final project that I created for Time Series Econometrics :)

PROJECT:
  The goal of this project was to see if there was any type of relationship between the skiing industry and daily snowfall. However
  I was unable to find a measure of the daily skiier count at these resorts or really any resorts for that matter. As a result I used
  Vail Resorts stock as the response variable for modeling the skiing industry. This ends up leading to some problems in the analysis
  however it is the best publically available option for this model. I fit end up fitting ARIMA models to the data and I wanted to fit
  a var model to the data if the ARIMA model was significant to prove causalty. However, there was no realtionship so there was no real 
  point in fitting an ARIMA model.

  Note some analysis of the predictors notably cOil and MTN occurs in hw3 file. I didn't feel like redoing it.

DATA:
  snowfall data was obtained from this link: https://www.kaggle.com/datasets/mrmarjo/resort-daily-snowfall-20092017
  The other data used in the analysis is pulled directly for either Yahoo Finance or FRED directly within the r code using an API.

