# Basic Data Exploration with pandas on Bikeshare Data
A python project using pandas to explore bikeshare data.

# Project Overview
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. 
Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. 
This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. 
Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. 
These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, you will use data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. 
You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

# The Datasets 
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:

Gender
Birth Year

The original files are much larger, and you don't need to download them, but they can be accessed here if you'd like to see them (Chicago, New York City, Washington). These files had more columns and they differed in format in many cases. Some data wrangling has been performed to condense these files to the above core six columns to make your analysis and the evaluation of your Python skills more straightforward.

# Insights Computed
Analyzed the data related to bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics

In this project, the following information were computed:
## 1. Popular times of travel (i.e., occurs most often in the start time):
* most common month
* most common day of week
* most common hour of day

## 2. Popular stations and trip:
* most common start station
* most common end station
* most common trip from start to end (i.e., most frequent combination of start station and end station)

## 3. Trip duration:
* total travel time
* average travel time
* most travel time
* minimum travel time
* maximum travel time

## 4. User info:
* counts of each user type
* counts of each gender (only available for NYC and Chicago)
* earliest, most recent, most common year of birth (only available for NYC and Chicago)

## 5. File indexing 
* Show 5 rows of the raw data

# Technologies Used:
* Python
* Numpy and Pandas
* Visual Studio Code
* Atom
* Terminal

# Credits:
[Udacity](https://udacity.com) - Thanks to the Udacity platform for providing the Programming for Data Science with Python Nanodegree program.
[Access Bank](https://accessbankplc.com) - Thanks to access bank for providing the opportunity for Africans to develop tech skills and advance their career.
[xhlow](https://github.com/xhlow) - xhlow's repository helped with understanding the structure and details of certain functions.
