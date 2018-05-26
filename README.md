# My First Project in Machine Learning Foundation Nanodegree
# Data Analysis
## Project: Exploring US Bikeshare Data 

<p align="center"><img src="US_Bike-share_logo.jpg"></p>


### Introduction

Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles for short trips, typically 30 minutes or less. Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, I will perform an exploratory analysis on data provided by [Motivate](https://www.motivateco.com/)</a>, a bike-share system provider for many major cities in the United States. I will compare the system usage between three large cities:
New York City, Chicago, and Washington DC.
I will also see if there are any differences within each system for those users that are registered, regular users and those users that are short-term, casual users. I will make use of Python(Pandas) to explore data and perform data wrangling to unify the format of data from the three systems and write code to compute descriptive statistics. I will also make use of a package that is not part of the standard Python library to help you visualize the data.

----

### Data for analysis

The data files for this analysis is in the above `data/` folder containing three csv files of the cities to be analyzed. Each of these cities has a page where we can freely download the trip data.:

New York City (Citi Bike): [Link](https://www.citibikenyc.com/system-data)<br>
Chicago (Divvy): [Link](https://www.divvybikes.com/system-data)<br>
Washington DC (Capital Bikeshare): [Link](https://www.capitalbikeshare.com/system-data)<br>

While the original data for 2016 is spread among multiple files for each city, the files in the `data/` folder collect all of the trip data for the year into one file per city. Some data wrangling of inconsistencies in timestamp format within each city has already been performed. In addition, a random 2% sample of the original data is taken to make the exploration more manageable.

After data wrangling process of the data files, the files are then saved to `output/` folder.


-----

