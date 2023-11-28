# python-api-challenge

# Assignment 1 - WeatherPy

# Description
This Python script WeatherPy analyzes weather data based on latitude. It includes scenarios for analyzing max temperature, humidity, cloudiness, and wind speed in both the Northern and Southern Hemispheres.
# Dependencies
- Python 3.x
- Required Python packages: pandas, matplotlib, requests

# Installation
1. Clone the repository.
2. Navigate to the project directory: `cd python-api-challenge`
3. Install dependencies: `pip install -r requirements.txt`

# Usage
Run the script with the command:
python weather.py
Data Sources
The script utilizes OpenWeatherMap API for fetching weather data. Please make sure to obtain an API key from OpenWeatherMap and replace it in the api_keys.py file.

# Results/Output
The script generates scatter plots and linear regression analysis for the following weather variables:

Max Temperature vs. Latitude
Humidity vs. Latitude
Cloudiness vs. Latitude
Wind Speed vs. Latitude
Results are saved in the output_data folder.

# Troubleshooting
If you encounter issues, Check that your OpenWeatherMap API key is correctly configured,save the config file and restart the kernel in Jupyter notebook.

# -----------------------------------------------------------------------------------------------------------------------------------#

# Assignment 2 - VacationPy

# Description
VacationPy is a Python script designed to help users plan their vacations by providing information about cities, weather conditions, and nearby hotels. The script uses various APIs to gather data and visualize it on an interactive map.

# Features
City Information: Obtain details about cities, including latitude, longitude, temperature, humidity, cloudiness, and wind speed.

Interactive Map: Visualize city data on an interactive map using hvplot, allowing users to explore locations and their characteristics.

Hotel Search: Find the nearest hotel for each city using the Geoapify API within a specified radius.

Hover Information: View additional details, including hotel names and countries, by hovering over city points on the map.

# Requirements
Python 3.x
Installation
Clone the repository

Copy code
pip install -r requirements.txt
Usage
Run the script

Copy code
python VacationPy
Follow the on-screen prompts to input your preferences for city selection and vacation planning.

Configuration
Adjust the search criteria in the script, such as temperature range, wind speed, and cloudiness, to tailor the vacation recommendations to your preferences.
Known Issues
Some cities may not have hotel information available in the Geoapify API, resulting in "No hotel found" messages.

