
# Python Rutgers Bootcamp Challenge - API Challenge 

This activity is broken down into two deliverables, WeatherPy and VacationPy.

## Description

In this assignment, I used the concepts I learned to begin working with APIs, using two API, OpenWeatherMap API and Geoapify, to analyze, manipulate, and 

## WeatherPY

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

![image](https://github.com/Connextstrategy/python-api-challenge/assets/18508699/5809c4d6-79d1-48de-bac1-4e4ffd0aa608)

You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.


## VacationPY

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

![image](https://github.com/Connextstrategy/python-api-challenge/assets/18508699/95ef2c89-7992-4387-b712-d79bd3c015b5)

2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

![image](https://github.com/Connextstrategy/python-api-challenge/assets/18508699/ce24cbff-2049-4586-a9ba-a0335a3e7416)


### Dependencies

* Must have GitBash used as an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience noting commands for analysis

* Must have Visual Studio Code 

### Installing

* Download the VBA raw data and copy and paste it while in VBA Developer mode in Excel. 
* No modifications needed to be made to files/folders

### Python Code - pybank & pypoll

* pybank Python code in folder named "pybank_solution"
* pypoll Python code in folder named "pypoll_solution"


## Help

No issues as it runs well on Microsoft Excel. Do recommend erasing the updated data to check the code every time. 

## Authors

Christopher Manfredi 

## Version History

    * Initial Release

## Acknowledgments

* This is specifically for an exercise for Rutgers Boot Camp 
