
# Weather and Vacation Data Analysis

In this project, I conducted data analysis on global weather data to gain insights into weather patterns across various cities and used the data to plan for ideal vacation destinations. The analysis involved gathering weather data using the OpenWeatherMap API, performing visualizations and statistical analysis, and utilizing geographical data to identify suitable vacation spots.

## Background

The project consists of two main parts:

### WeatherPy

In the WeatherPy section, I collected weather data for over 500 cities worldwide, visualized the relationships between weather parameters (such as temperature, humidity, cloudiness, and wind speed) and latitude using scatter plots, and conducted linear regression analysis. The purpose was to explore how weather conditions vary with proximity to the equator.

### VacationPy

In VacationPy, I utilized the weather data obtained in WeatherPy to identify potential vacation destinations with favorable weather conditions. I used Jupyter-gmaps and the OpenWeatherMap API to create interactive heatmaps of humidity levels across cities. Then, I narrowed down the list of cities based on specific weather criteria and used the Google Places API to find nearby hotels for each destination. Finally, I plotted the chosen hotels on the heatmap to visualize ideal vacation spots.

## Observations and Insights

Here are some key observations and insights from the analysis:

- Temperature tends to decrease as distance from the equator increases, with cities closer to the equator experiencing higher temperatures.
- There is no strong correlation between latitude and cloudiness or wind speed, indicating that these factors are influenced by other variables.
- VacationPy analysis helped identify vacation destinations with pleasant weather conditions, including moderate temperatures, low humidity, and clear skies.


## Images

Static images generated during the VacationPy analysis can be found [here](./WeatherPy/output_data/map_perfect_weather_hotels.png) and [here](./WeatherPy/output_data/map_point_city_data.png).


## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- OpenWeatherMap API
- GeoViews

## References

- OpenAI ChatGPT: https://openai.com/chatgpt
- Pandas documentation: https://pandas.pydata.org/docs/
- Matplotlib documentation: https://matplotlib.org/contents.html
- Jupyter Notebook documentation: https://jupyter-notebook.readthedocs.io/en/stable/
- OpenWeatherMap API documentation: https://openweathermap.org/api
- GeoViews documentation: https://geoviews.org/
- Stack Overflow: https://stackoverflow.com/
- Python documentation: https://docs.python.org/3/

