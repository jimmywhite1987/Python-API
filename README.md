# Python API

## Part I - WeatherPy

Utilize a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Part II - VacationPy

* Create a heat map that displays the humidity for every city from Part I.

* Narrow down the DataFrame to find your ideal weather condition. For example:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

# `Climate Analysis`

## Project Description

-  The goal of this project is to utilize the [CitiPy Python Library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.
- Then, create a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude
- Then, run linear regression on each relationship. This time, separate the plots into Northern Hemisphere and Southern Hemisphere:
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
- Using the data from the first half of this project, then create a heat map that displays the humidity for every city from Part I.
- Finally, narrow down the DataFrame to find the "ideal" weather condition, use Google Places API to find the first hotel for each city located within 5000 meters of the coordinates and plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.


## Languages & Technology Used

- Python
- Pandas
- Jupyter Notebook
- CitiPy
- Open Weather Map API
- Google Places API

## Screenshots
![image](/Images/Hotel_Map.png)

![image](/Images/latitude_vs_cloudiness.png)

![image](/Images/latitude_vs_humidity.png)

![image](/Images/latitude_vs_temp.png)

![image](/Images/latitude_vs_windspeed.png)

![image](/Images/northern_cloudiness_latitude.png)

![image](/Images/northern_humidity_latitude.png)

![image](/Images/northern_temp_latitude.png)

![image](/Images/northern_windspeed_latitude.png)

## Links
- [JWhiteAnalytics.com](https://jwhiteanalytics.com)
- [LinkedIn](https://www.linkedin.com/in/jimmywhite1987)
