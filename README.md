"# Random_Forest_Weather_Forecast_Model" 
# Random_Forest_Weather_Forecast_Model

In the problem statement, we have one year of weather data. We have to predict tomorrow’s temperature.  NOAA Climate Data Online tool helps us to get the data of our city.
Data we have:
	One year of historical MAX temperature
	Temperature of previous 2 days
	An estimate from friend who claims to know everything about Weather

 	This is a SUPERVISED REGRESSION Machine Learning problem – it is SUPERVISED because we have both x and y , i.e. we have features(data for the city) ->X and we have target(temperature) ->Y
 	During TRAINING, we give the model both the features & target
 	The model must learn how to map the data so as to predict
 	It is REGRESSION problem because the Target is continuous (not discrete). If the Target is discrete (like levels of classes) then it is CLASSIFICATION problem.

ROADMAP
1.	Define problem statement and required data
2.	Get the Data in accessible format
3.	Identify the anomalies/outliers and correct them as per the requirement
4.	Prepare the data for Machine learning Model
5.	Establish a baseline model you aim to exceed (in terms of accuracy)
6.	Train the data on a training data
7.	Make predictions on the test data
8.	Compare the predictions with known test 
9.	Evaluate the predictions with known test set targets and calculate the performance
10.	If performance is not good, tune the model or acquire more data, try different model
11.	Interpret the model and show the results visually or numerically

