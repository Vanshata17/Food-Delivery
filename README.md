# Food-Delivery
To predict the food delivery time in real-time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.
The dataset doesn’t have any feature that shows the difference between the restaurant and the delivery location. All we have are the latitude and longitude points of the restaurant and the delivery location. We can use the haversine formula to calculate the distance between two locations based on their latitudes and longitudes.
the features that contribute most to the food delivery time based on our analysis are:
-age of the delivery partner
-ratings of the delivery partner
-distance between the restaurant and the delivery location

I have trained a Machine Learning model using an LSTM neural network model for the task of food delivery time prediction
