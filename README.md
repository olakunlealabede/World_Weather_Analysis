# World Weather Analysis

Project Plan Outline:

Task: To Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will be using the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with over 600 or more of the world's unique cities and their weather data in real time. This process entails collecting, analyzing, and visualizing the data. The analysis of the data will be split into three main parts, or stages.
Collect the Data
NumPy module is being used to generate 2,000 random latitudes and longitudes.
Citipy module is being used to list the nearest city to the latitudes and longitudes.
OpenWeatherMap API will be used to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
The following data is being collected from the JSON file and added to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed

Exploratory Analysis with Visualization

Create scatter plots of the weather data for the following comparisons:

Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed

Determine the correlations for the following weather data:

Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed

Create a series of heatmaps using the Google Maps and Places API that showcases the following:

Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed

Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.

Create a heatmap for the new DataFrame.

Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.

Store the name of the first hotel in the DataFrame.

Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

![image](https://user-images.githubusercontent.com/89113627/137672041-029a4003-6c97-4306-8bd0-e1e2dc362171.png)

# Deliverable 2: Create a Customer Travel Destinations Map

# Hotel_df DataFrame

![image](https://user-images.githubusercontent.com/89113627/137673123-92b60974-95a7-482a-b16e-d42d78c43373.png)

# The marker layer map with a pop-up marker for each city should look similar to the following image:

![image](https://user-images.githubusercontent.com/89113627/137672424-fa2640a2-d696-4d7e-9af4-b8160a1bcc1c.png)

# Deliverable 3: Create a Travel Itinerary Map

![image](https://user-images.githubusercontent.com/89113627/137674357-46861e6d-c47a-4817-931b-d0eac16d8749.png)


