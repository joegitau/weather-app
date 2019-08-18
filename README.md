# weather-app
A Node.JS powered Weather Application.


Devloped using NODE.JS, The Weather API, takes into use depedencies including Express, Joi, 
Request among others. It also puts into use the HBS Templating Engine to render the HTML pages.

As the title suggests, the application's core use is to provide current weather conditions for all locations in the world.

To facilitate this, the application fetches data from two APIs namely: 


1. Dark Sky API:
   The Dark Sky API offers a full collection of meteorological conditions in 39 different languages. 
   The API allows you to look up the weather anywhere on the globe, returning where available ->
   - Current weather conditions
   - Minute-by-minute forecasts out to one hour
   - Hour-by-hour and day-by-day forecasts out to seven days
   - Hour-by-hour and day-by-day observations going back decades
   
2. MapBox Geocoding API:
   The Mapbox Geocoding API does two things: forward geocoding and reverse geocoding.
    - Forward geocoding converts location text into geographic coordinates
    - Reverse geocoding on the other hand turns geographic coordinates into place names.
    

In summary; 

The functionality of the application requires that both APIs work in tandem to effectively provide data to a user. Once a user types in a city, country or the postal code of a particular location, the data is sent to the Mapox API which converts the text into coordinates which are then mapped as query strings in the DarkSky's endpoints to finally provide the relevant response, in this case, the weather conditions of that particular user search text.

The Front-end uses HBS, template engine which also includes minor features such as background color changes depending on a locaton's time of dat.

Enjoy.


Developed with 💜 by Joseph Gitau


