# Python API Challenge
Repository for Module 6 Challenge

## Introduction

This project delves into the fascinating world of weather patterns and vacation planning using data fetched from the OpenWeatherMap API and Geoapify API. By leveraging Python's powerful libraries and APIs, this project answers the age-old question: "What is the weather like as we approach the equator?" and goes a step further by using weather data to plan ideal vacation spots.

## Part 1: WeatherPy

### Objective

The goal of WeatherPy is to analyze the weather of 500+ cities across the world of varying distances from the equator. By utilizing Python requests, APIs, and JSON traversals, this analysis creates a representative model of weather across cities.

### Methodology

- **Data Retrieval:** Utilize the citipy library to select over 500 unique (non-repeat) cities based on latitude and longitude.
- **API Calls:** Fetch weather data for each city using the OpenWeatherMap API.
- **Data Analysis:** Analyze and visualize the weather data to uncover trends related to latitude.

### Key Deliverables

- Scatter plots that showcase the relationship between latitude and various weather parameters (temperature, humidity, cloudiness, wind speed).
- Linear regression models for the Northern and Southern Hemispheres for each weather parameter.
- Analysis of the results, highlighting trends and the impact of latitude on weather conditions.

## Part 2: VacationPy

### Objective

Using weather data collected in WeatherPy, VacationPy aims to identify ideal vacation spots based on specific weather criteria. Additionally, it uses the Geoapify API to locate hotels within these ideal locations.

### Methodology

- **Data Filtering:** Apply weather criteria (e.g., temperature range, wind speed, cloudiness) to narrow down cities.
- **Hotel Search:** For each city meeting the criteria, find hotels within a 10,000-meter radius using the Geoapify API.
- **Mapping:** Utilize geoViews and the Geoapify API to create interactive maps displaying the filtered cities and hotels.

### Key Deliverables

- An interactive map marking the cities with ideal weather conditions.
- Another map pinpointing hotels within these cities, including additional information such as hotel name and country in the hover text.

## Technologies Used

- Python: For scripting and data analysis.
- Pandas: For data manipulation and analysis.
- Matplotlib: For creating scatter plots and linear regression models.
- Jupyter Notebook: For compiling the analysis and visualizations.
- OpenWeatherMap API: For fetching real-time weather data.
- Geoapify API: For fetching hotel data and generating maps.
- Citipy: For determining city names based on latitude and longitude.

## Skills Demonstrated

This project showcases a range of data analytics skills, including:

- Effective use of APIs to fetch data.
- Data cleaning and preparation for analysis.
- Advanced data visualization techniques.
- Application of statistical models to understand data trends.
- Use of mapping tools to visualize geographical data.

## Conclusion

The Python API Challenge provides a comprehensive analysis of global weather patterns, demonstrating the influence of latitude on weather conditions. Through creative data visualization and statistical analysis, this project offers valuable insights into the relationship between geographical location and weather. Additionally, it leverages these insights to aid in the planning of vacations, showcasing the practical application of data analytics skills in real-world scenarios.

For detailed insights, analysis, and visualizations, please refer to the `WeatherPy.ipynb` and `VacationPy.ipynb` notebooks within this repository.


