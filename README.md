# Final project

Please read this before accesing our final project. Our project is about weather and health for a better day. The Weather Recommendation App is a web-based application designed to provide users with real-time weather information for a specified city. It goes beyond presenting basic weather metrics, offering personalized clothing and activity recommendations based on the current and forecasted weather conditions.

## Features:

### City-based Weather Information: 
Upon entering the name of a city, users receive real-time data about the current temperature, humidity, wind speed, and general weather conditions for that location.

### Interactive City Map: 
An integrated map displays the geographic location of the entered city, providing visual context to users.

### Clothing Recommendations: 
The app suggests appropriate clothing items based on the current weather conditions. This way will our user stay healthy during the whole year!

### Activity Recommendations: 
In addition to clothing suggestions, the app proposes activities that are suitable for the current weather. 

### Three-Day Weather Forecast: 
Users are not limited to just current weather data. The app provides an average temperature and weather conditions for the upcoming three days, assisting users in planning ahead.

### Educational Link: 
A Wikipedia link related to the entered city is provided, allowing users to learn more about their location of interest.

## Details:
The application is developed using Flask, a micro web framework written in Python. Real-time weather data and forecasts are fetched from the OpenWeatherMap API. City geolocation details are obtained using the Geopy library's Nominatim geocoder. Additionally, the Wikipedia API is used to retrieve relevant city-based Wikipedia links. The user interface is built using HTML templates, with interactive map functionality provided by the Leaflet JavaScript library.
