# Food-Delivery
To predict the food delivery time in real-time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.
The dataset doesn’t have any feature that shows the difference between the restaurant and the delivery location. All we have are the latitude and longitude points of the restaurant and the delivery location. We can use the haversine formula to calculate the distance between two locations based on their latitudes and longitudes.
the features that contribute most to the food delivery time based on our analysis are:
-age of the delivery partner
-ratings of the delivery partner
-distance between the restaurant and the delivery location

I have trained a Machine Learning model using an LSTM neural network model for the task of food delivery time prediction. In machine learning tasks such as time series forecasting or sequence prediction, capturing and modeling temporal dependencies is crucial for making accurate predictions. Models like LSTM (Long Short-Term Memory) and other recurrent neural networks (RNNs) are specifically designed to handle temporal dependencies by retaining information from past time steps and incorporating it into predictions for future time steps.There may be a temporal dependency between the time taken for a delivery and the time of day, as delivery times may vary depending on traffic conditions during different times of the day.
Delivery times for orders placed during peak hours may be influenced by the number of orders in the queue and the availability of delivery partners, leading to temporal dependencies between order volume and delivery times.
