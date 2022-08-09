# World_Weather_Analysis - Module 6 

## Overview  

The Plan My Trip App was a success with the beta testers and it is now time to take it to the next level.  So, we have been asked to add in weather description to our weather module, allowing our users another item preference to sort and search on.  We will overlay this with hotels that are in the vicinity and help them plan out their trip itinerary to the locations of their chokings.

### Retrieve the Weather Data 

-  Retrieve all of the following information from the API call
     - Latitude and longitude
     - Maximum temperature
     - Percent humidity
     - Percent cloudiness
     - Wind speed
    - Weather description (for example, clouds, fog, light rain, clear sky)
-  Add the weather data to a new DataFrame 

### Travel Destination Map

  - Prompt the customer for their minimum and maximum temperature preferences. 
  - DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped. 
  - The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped. 
  - The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv. 
  - A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 
     - Hotel name
     - City
    - Country
  
  - Current weather description with the maximum temperature
  
### Travel Itinerary Map  

  - The latitude and longitude pairs for each of the four cities are retrieved.
  - A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. 
  - A DataFrame that contains the selected cities on the itinerary is created. 
  - A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the         following information: 
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature

## Challenge

The challenge required use of Google Maps and Open Weather API's along with continued uses of Panda's and Python knowledge.  It was challenging to overlay it all together and get it to work correctly.  I had the first portion of this challenge take way longer than it should all becasue I forgot to put "" around the word description.  I would say this was the most intensive challenge so far that utilized all of my skills to date.

