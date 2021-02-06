# Challenge 6: World Weather Analysis

## Overview of The World Weather Analysis
This repository contains three jupyter notebooks:
- [Weather_Database.ipynb](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb)
    1. Creates 2,000 random latitudes and longtitudes
    2. Generates a list of cities near these locations
    3. Finds current weather information for these cities - where available
    4. Stores the results in [WeatherPy_Database.csv](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv) 

- [Vacation_Search.ipynb](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb)
    1. Asks the user for minimum and maximum temperatures for a potential vacation destinations (25°C and 35°C were entered)
    2. Filters the cities based on the provided temperature range
    3. Finds a hotel within 5km of each city - where avavialble
    4. Creates a map with annotated markers for the results
    ![WeatherPy_vacation_map.png](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
    5. Saves the cities with hotels in [WeatherPy_vacation.csv](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)

- [Vacation_Itinerary.ipynb](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)
    1. Select an initial city and three other cities in the same country 
    2. Plots the driving directions from the initial city through the three additional cities and back to the initial city
    ![WeatherPy_travel_map.png](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
    3. Finally, plots the initial and additional cities with markers
    ![WeatherPy_travel_map_markers.png](https://github.com/Hala-INTJ/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)