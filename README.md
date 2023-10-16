# Python API Challenge: Module 6

## Objective

The goal of this challenge was to pull live information from OpenWeather API to plot different variables in the weather and highlight the relationships they might have to its distance from the equator. Once plotted, the WeatherPy code analyzes the linear regressions for both plots in the Northern and Southern Hemispheres to get a better idea of what correlations exist between these variables and their respective latitudes from the equator.

After this information was analyzed, in the VacationPy code, the resulting data was compiled and utilized to plot maps for target destinations based on specific weather conditions. Afterwards a quick snapshot of the local accommodations for these locations was generated on an open source map using the Geoapify API.

## Attributions

In order to format the timestamps pulled from OpenWeather API, I used information from "https://docs.python.org/3/library/datetime.html" to learn about and use .strftime. Other information for this project was sourced from the following: <br>
"https://openweathermap.org/"<br>
"https://www.geoapify.com/"<br>
Map data from OpenStreetMap<br>
