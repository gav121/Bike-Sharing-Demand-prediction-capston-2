# Bike Sharing Demand prediction-capstone-2

Creating a machine learning model for bike demand prediction

![large](https://user-images.githubusercontent.com/63629019/179600364-0dac602c-f570-4411-b567-dca16bb19d77.jpg)

INTRODUCTION

A bike sharing system is a service in which bikes are made available for shared use by individuals for a short period of time at a cost or for free. Many bike-sharing systems allow people to borrow a bike from a "dock," usually controlled by a computer, where the user enters payment information and the system unlocks it. This bike can then be returned to another dock that belongs to the same system. Rental Bike Sharing is a process where bikes are acquired on several basis – hourly, weekly, membership etc. This phenomenon has seen the inventory increase to a significant level due to global efforts to reduce the carbon footprint which leads to climate change. , unprecedented natural disasters, depletion of the ozone layer and other ecological anomalies. In our project, we decided to analyze a data set related to the demand for bicycle rentals from the South Korean city of Seoul, which includes climate variables such as temperature, humidity, precipitation, snowfall, dew point temperature, and more. The available raw data was first pre-processed, after which the number of bike rental hours is regressed here. Our linear model was able to explain to some extent the factors that drive the hourly demand for bicycle rentals.



PROBLEM STATEMENT

Maximize: The availability of bikes to the customer.
Minimize: Minimise the time of waiting to get a bike on rent.

The main goal of the project is:
Search factors and causes that affect the lack of a bike and the time delay of a rental bike. Based on the data provided, the objective of this paper is to analyze the data and determine what variables, if any, correlate with churn. The hourly number of bikes to rent will also be predicted.

FEATURE BREAKDOWN


Date: The date of the day, during 365 days from 01/12/2017 to 30/11/2018, formatting in DD/MM/YYYY, we need to convert into date-time format. 
Rented Bike Count: Number of rented bikes per hour which our dependent variable and we need to predict that
Hour: The hour of the day, starting from 0-23 it's in a digital time format
Temperature (°C):  Temperature of the weather in Celsius and it varies from -17°C to 39.4°C.
Humidity (%): Availability of Humidity in the air during the booking and ranges from 0 to 98%.
Wind speed (m/s): Speed of the wind while booking and ranges from 0 to 7.4m/s.
Visibility (10m):  Visibility to the eyes during driving in “m” and ranges from 27m to 2000m.
Dew point temperature (°C):Temperature
At the beginning of the day and it ranges from -30.6°C to 27.2°C.
Solar Radiation (MJ/m2):  Sun contribution or solar radiation during ride booking which varies from 0 to 3.5 MJ/m2.
Rainfall (mm): The amount of rainfall during bike booking which ranges from 0 to 35mm. 
Snowfall (cm): Amount of snowing in cm during the booking in cm and ranges from 0 to 8.8 cm.
Seasons: Seasons of the year and total there are 4 distinct seasons I.e. summer, autumn, spring and winter.
Holiday: If the day is holiday period or not and there are 2 types of data that is holiday and no holiday 
Functioning Day: If the day is a Functioning Day or not and it contains object data type yes and no.

CONCLUSIONS

Bike sharing systems may be the new boom in India, with the use of various predictive models to streamline traffic. Four algorithms are applied to a bike-sharing dataset to predict the number of bikes that will be rented per hour. We got good results and accuracy with random forest. Accuracy and performance were compared between models using Root Mean Squared Error (RMSE), Mean Squared Error (MSE), Mean Absolute Error (MAE), R2 and Adjusted R2. If these systems include the use of analytics, the likelihood of building a successful system increases

