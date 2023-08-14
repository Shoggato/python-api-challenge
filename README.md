# World Weather API calls and Vacation Ideas

## Table of Contents

- [Background](#background)
- [About](#about)
- [Contributing](#contributing)

# Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

# About

Using two API's Weather API, and Geoapify API.  I pull random city data points from all over the globe and analze these points based on different criteria (Temperature, cloudiness, humidity, wind speed) and how they compare between the two hemispheres.  The second part of this project, was taking the data points, filtering them based on what I think would be nice vacation weather.  Then using Geoapify API look for the closest hotels near these cities.  Maybe I will find my next vacation destination?

Within the python-api-challenge github, you will find three folders.  Output_data, VacationPy, WeatherPy.  

Output_data folder: 
Holds any information that needs to be saved such as figures and the data cities.csv that is pulled from the internet using Weather API.  
figures that were saved:

![image](<output_data/Fig1.png>)

![image](<output_data/Fig2.png>)

![image](<output_data/Fig3.png>)

![image](<output_data/Fig4.png>)

WeatherPy folder:
Stores the Jupyter notebook file, along with two other Python files.  linearregression.py.

WeatherPy:
This first part of my project uses the Weather API to locate randomly cities all over the world.  Then further analysis of the data split between the northern and Southern Hemispheres.  

linearregression.py:
This function utilizes five inputs, two of these are different data sets that need to be compared (x, y).  Three other inputs that will label the x_axis, y_axis, and the title of the plot.  Once the functions five inputs are satisfied it will compute the linear regression line utilizing scipy linregress function and matplotlib.pyplot for plotting both the scatter graph and the linear regression line.

VactionPy:
Holds my second part of my project VacationPy Jupyter notebook.  This takes the cities found in the WeatherPy and then filters them by different criteria I think would make for a lovely vacation spot.  Then finds the closest hotels.

# Contributing
Erika Walker

