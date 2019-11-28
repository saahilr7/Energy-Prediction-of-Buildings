# Energy-Prediction-of-Buildings
Problem Statement:
If an organization wants to construct a new building, what will be its energy consumption based on various infrastructural needs and environmental factors?

Questions asked:
•	What will be the energy consumption of a new building?
•	With various factors like season, building size, weather condition, location involved, what could be the energy meter reading of the building?

Source of Data:
The dataset is from a competition by American Society of Heating, Refrigeration, Cooling and Air conditioning Engineers on Kaggle. 
Link:  https://www.kaggle.com/c/ashrae-energy-prediction/data

Understanding Data: 
The raw data we obtained had three datasets:
1.	Building dataset - contained details like building size, No of Floors 

2.	Weather dataset - contained columns like Air temperature, dew temperature, Wind speed, sea level pressure and other environmental factors

3.	Train dataset- contained the variable Meter reading for each building, which is our dependent variable on which we are trying to predict. 
We have merged the three datasets into one and are splitting it into train and test.

Questions answered:
We started out with couple of problem statements in mind. After the predictions we can safely say that we are answering them with good accuracy.
•	We are predicting the meter reading or energy a particular type of buildings consumes.
•	This information can be used for planning future building constructions with reduced cost and energy emissions.
