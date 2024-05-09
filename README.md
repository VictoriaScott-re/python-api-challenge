
# Weather and Vacation Data Analysis

In this project, I conducted data analysis on global weather data to gain insights into weather patterns across various cities and used the data to plan for ideal vacation destinations. The analysis involved gathering weather data using the OpenWeatherMap API, performing visualizations and statistical analysis, and utilizing geographical data to identify suitable vacation spots.

## Background

The project consists of two main parts:

### WeatherPy

In the WeatherPy section, I collected weather data for over 500 cities worldwide, visualized the relationships between weather parameters (such as temperature, humidity, cloudiness, and wind speed) and latitude using scatter plots, and conducted linear regression analysis. The purpose was to explore how weather conditions vary with proximity to the equator.

### VacationPy

In VacationPy, I leveraged the weather data obtained from WeatherPy to pinpoint potential vacation destinations featuring favorable weather conditions. Using Geoviews and the OpenWeatherMap API, I crafted interactive heatmaps showcasing humidity levels across various cities. Subsequently, I refined the list of cities based on predetermined weather criteria. Finally, I plotted the chosen cities onto a world map and identified nearby hotels using Geoviews Feature.

## Observations and Insights

Here are some key observations and insights from the Weatherpy analysis:

- Temperature tends to decrease as distance from the equator increases, with cities closer to the equator experiencing higher temperatures.
- There is no strong correlation between latitude and cloudiness or wind speed, indicating that these factors are influenced by other variables.
- VacationPy analysis helped identify vacation destinations with pleasant weather conditions, including moderate temperatures, low humidity, and clear skies.


## Images

Static images generated during the VacationPy analysis can be found [here, hotels](output_data/map_perfect_weather_hotels.png) and [here, city data](output_data/map_point_city_data_df.png).


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

