## Business Problem
Weather, and humankind's ability to accurately predict it, plays a critical role in many aspects of life. From farmers growing crops to a family planning a weekend vacation to logistical decision making within airlines, rain in particular is highly influential regarding plans. In some instances, the impact of rain can have large financial consequences. As a result, there is a strong interest from a plethora of stakeholders in the ability to accurately forecast rain. The goal of this project is to use the available data to create a next-day prediction model for whether or not it will rain. Such a model could be utilized in our app to predict rain-tommorow


### Data Source
The data used in this project was downloaded from the Kaggle dataset titled Rain in Australia, which itself was originally sourced from the Australian Bureau of Meteorology's Daily Weather Observations. 

https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

## Data Description
Date: The date of observation  
Location: The common name of the location of the weather station  
MinTemp: The minimum temperature in degrees celsius  
MaxTemp: The maximum temperature in degrees celsius  
Rainfall: The amount of rainfall recorded for the day in mm  
Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9am  
Sunshine: The number of hours of bright sunshine in the day.  
WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight  
WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight   
WindDir9am: Direction of the wind at 9am  
WindDir3pm: Direction of the wind at 3pm  
WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am  
WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3pm  
Humidity9am: Humidity (percent) at 9am  
Humidity3pm: Humidity (percent) at 3pm  
Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am  
Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm  
Cloud9am: Fraction of sky obscured by cloud at 9am.  
Cloud3pm: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm.  
Temp9am: Temperature (degrees C) at 9am  
Temp3pm: Temperature (degrees C) at 3pm  
RainToday: Did the current day receive precipitation exceeding 1mm in the 24 hours to 9am. Binary (0 = No, 1 = Yes)  
RainTomorrow: Did the next day receive precipitation exceeding 1mm in the 24 hours to 9am. Binary (0 = No, 1 = Yes)  

## Model architecture 


We employed  5  models and fine-tuned it for our particular rain detection task. & we fined that conv1d is best layer for that task

![image](https://user-images.githubusercontent.com/31762490/202327821-c78f1577-083e-466a-b7c4-0b17df5c243e.png)


