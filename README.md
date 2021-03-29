# World_Weather_Analysis

### Overview
PlanMyTrip is an app that allows users to find travel destinations, nearby hotels and possible itineraries between chosen cities based on their weather preference. Below is a summary of the steps used in the code: 

1. Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap to retrieve weather data for those cities.

 ![image](https://user-images.githubusercontent.com/79415699/112777387-2506a100-9010-11eb-8fa0-91127f4ccd56.png)

2. Retrieve customer weather preferences, and use them to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.
![image](https://user-images.githubusercontent.com/79415699/112777474-52534f00-9010-11eb-9411-9eeaca5e48de.png)

3. Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

![image](https://user-images.githubusercontent.com/79415699/112777509-6e56f080-9010-11eb-93e6-89f11ac461cc.png)


![image](https://user-images.githubusercontent.com/79415699/112777569-8d558280-9010-11eb-80dc-1b0eb77b6ef7.png)
