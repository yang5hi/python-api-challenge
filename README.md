# python-api-challenge
key words: OpenWeather API, Google Places API, citipy, gmaps

# Background
The project ulitizes the OpenWeather API and Google API to find the weather for a set of geographic cities with population over 500. Then the list of cities is reduced with locations and weather critiria. With the final city set, the hotels were listed for each cities under Google API search results.

# Part I - WeatherPy
* A series of scatter plots were created to showcase the following relationships:
  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude
  * Wind Speed (mph) vs. Latitude
* The plots above were then seperated into Northern Hemisphere and Southern Hemisphere. Linear regression were done on the following eright graphes.
  * Northern Hemisphere - Temperature (F) vs. Latitude
  * Southern Hemisphere - Temperature (F) vs. Latitude
  * Northern Hemisphere - Humidity (%) vs. Latitude
  * Southern Hemisphere - Humidity (%) vs. Latitude
  * Northern Hemisphere - Cloudiness (%) vs. Latitude
  * Southern Hemisphere - Cloudiness (%) vs. Latitude
  * Northern Hemisphere - Wind Speed (mph) vs. Latitude
  * Southern Hemisphere - Wind Speed (mph) vs. Latitude 
# Part II - VacationPy
* Heat map that displacys the humidity for every city from Part I was created.
* The city list is reduced to less than 10 based on weather conditions.
* Google Places API was used to find the first hotel for each city located within 5000 meters of the city coordinates.
* The hotels were marked on top of the humidity heatmap with each pin containing the Hotel Name, City and Country. 
