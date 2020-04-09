# Airline-Food-Sales-Analysis

About the data:
The data is simulated data intended to approximate a real-world dataset you may encounter at the airline. The Airline’s most popular inflight meal is the Signature Fruit and Cheese Platter. This dataset shows the number of cheese platters sold on 5,000 simulated flights, along with information about the flights the cheese platters were sold on.
-	Dptr Hour: the time (rounded to the hour) when the flight departed
-	Length of Flight (Hrs): the length of the flight rounded to the hour
-	Day of Week: the day of the week the flight took place on
-	Passengers Boarded: the number of passengers on board the flight
-	Stock Out Occurred: 1 = inflight crew reported that the last platter was sold
-	Cheese Platters Sold: the number of cheese plates that were sold
Main Titles:
1.	Investigate the Data
-	Are there any identifiable patterns between each of the variables and the number of cheese platters sold?
-	What are the distributions of each of the variables?
2.	Constraints
-	Which of the variables in the dataset appear to be truncated/censored?
-	Infer and explain in real-life terms why they are truncated/censored.
3.	Estimating Demand
-	Demand in this context is defined by the number of cheese platters we could have sold (which will be >= to the number we actually sold). Create a multivariate regression model that estimates the demand for cheese platters on the flight grain [i.e. demand or a proxy for it should be the dependent variable].
-	Use the patterns you found above in prompt 1 to design the functional form of the regression model. Discuss how the independent variables relate to demand.
-	How did you judge if your regression model was working well?
