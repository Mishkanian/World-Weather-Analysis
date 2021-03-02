# World Weather and Vacation Planner

## Project Overview
The purpose of this project is to create a Python script for a hypothetical travel company that will use input statements to filter potential travel destinations worldwide. After selecting four cities to create a travel itinerary, Google Maps Platform APIs are used to create travel routes and a markup map.

## Software and APIs
**Software:** Python 3.7, Anaconda, Jupyter Notebook.

**Google Maps Platform:** Directions API, Places API.  
To set up a new gmap API key, [click here](https://developers.google.com/maps) and select "Get Started."

**OpenWeatherMap:** Current Weather Data.  
To set up a new OpenWeatherMap API key, [click here](https://home.openweathermap.org/users/sign_up) to create a free account.  

For this project, it is also necessary to create a config.py file with your specific API key information, please see the example below. Do not upload or share your API key information with anyone. It is recommended to add "config.py" to the gitignore to keep your key information private.
```
weather_api_key="your-weather-api-key-here"
g_key="your-google-maps-api-key-here"
```

## Gatering City and Weather Data  
To start this project, it was necessary to create a data file containing city information, including weather and location data. I began by generating a random set of 2,000 latitude and longitude combinations using the NumPy .random.uniform() method.

## Generating a Worldwide Travel Map  
Using the CSV data file generated in the previous section, 

## Creating a Travel Itinerary  


**Author: Michael Mishkanian**  

For all questions and inquiries, please contact me on [LinkedIn](https://www.linkedin.com/in/michaelmishkanian/).
