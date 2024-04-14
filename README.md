# Hourly-Energy-Consumption

Energy plays a vital role in our day-to-day life. Energy Production and energy
Consumption are the two important terms. In our project we are going to predict about the energy consumption for next years based on energy, which was consumed during the peak hours, peak days and weeks. This was done by Time series forecasting Method. A time series is a sequence of data points being recorded at specific times. For example in our project the scenario is the energy consumption is in peak during the Sundays (weekends). Comparing Morning and evening the energy consumption rate is higher in the evening. We have to record the data in this peak time and this is the basic need for our prediction. We also use prophet method in our project. The Data Frame method is the one which is useful for you plotting the points in seasonal manner like weekly, hourly and daily energy consumption. The data we have in our project is Date & Time with Megawatt (MW) produced. Based on this we use regression is a technique because the class label is a numerical value. Prophet() object takes arguments to configure the type of model you want, such as the type of growth, the type of seasonality, and more.
