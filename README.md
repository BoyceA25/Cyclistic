# Cyclistic
Google Data Analytics Capstone

# Introduction

Hello, my name is Andrew and I am an aspiring Data Analyst. I am completing the Google Data Analytics Certification course as my first step in my Data Analytics career. I am hoping that I can use my drive and passion for technology and data to learn and grow my analysis skills. I have experience working with large databases and am looking forward to see how I can implement those skills into analyzing data. This notebook will cover my first Data Analyst case study. The data was provided through the certification course and was cleaned/processed using R Studio. Afer analyzing the data, I created some visualizations using Tableau.

# Background Information

Cyclistic is a bike sharing program that began in 2016 and has rapidly expanded to include over 5,800 bikes and 600 docking stations. What sets Cyclistic apart is its dedication to inclusivity, offering reclining bikes, hand tricycles, and cargo bikes to cater to individuals with disabilities or those who cannot use traditional two-wheeled bikes.

The bikes in the fleet are equipped with geotracking technology and are connected to a network of 692 stations spread throughout Chicago. This interconnected system allows users to unlock bikes from one station and return them to any other station within the network at their convenience.

Previously, Cyclistic's marketing strategy focused on raising overall awareness and appealing to a wide range of consumers. They offer flexible pricing plans, including single-ride passes, full-day passes, and annual memberships. Casual riders opt for single-ride or full-day passes, while those who choose annual memberships become official Cyclistic members.

# ASK

My primary objective as a data analyst is to show how Cyclistic can optimize the number of annual memberships by converting casual customers (single-ride and day passes) into long-term members (annual membership). To achieve this, our data analysis will focus on discerning the distinct usage patterns between casual riders and annual members of Cyclistic bikes.

# Prepare

The data that I am using for this capstone was collected by Motivate International Inc an available under the following licesnse: https://ride.divvybikes.com/data-license-agreement. The RStudio packages that I am going to be utilizing are tidyverse, lubridate, janitor, hms, and scales. The Tidyverse, lubridate, and ggplot2 packages were covered in the Google Data Analytics course, but I wanted to explore a few new packages, so I made sure to take advantage of janitor for cleaning, hms for formatting dates, and scales for setting the scale to look better on the RStudio plots.

# Process

First, I need to bring in all of my bike share data from the seperate month CSV files that were provided. I am reading in the CSV files using the 'read_csv' function and converting them into dataframes. This will allow for me to combine all of the data into one single large dataframe.

Secondly, after taking in all of the data and setting up my dataframes, I need to process the data furhter so we have a more clear and defined table.

# Analyze

The next step of my data analytics investigation is to analyze the data so we are able to draw meaningful conclusions from what we are seeing. This includes creating new variables that we can use down the line to create some in-depth visualizations.

# Share

Now that the data has been analyzed we can start making some visualizations to express the conclusions we have drawn in our analysis.

![Average Ride Length](https://github.com/BoyceA25/Cyclistic/blob/main/AvgRideLength.png?raw=true) 
![Number Bikes](https://github.com/BoyceA25/Cyclistic/blob/main/NumBikesPerType.png?raw=true) 
![Number Rides](https://github.com/BoyceA25/Cyclistic/blob/main/NumRidesbyMemType.png?raw=true) 
![Percent Member](https://github.com/BoyceA25/Cyclistic/blob/main/PercentMemberType.png?raw=true) 
![Rides by Week](https://github.com/BoyceA25/Cyclistic/blob/main/RidesPerWeekDay.png?raw=true) 
![Rides Time of Day](https://github.com/BoyceA25/Cyclistic/blob/main/RidesTimeDay.png?raw=true) 


# Act

For the last step in the data analysis process, we will make three recomendations to increase our annual membership. But first, we will make three key insights.

#### Recommendations:
* Create more advertisements on how memberships save money for those who ride a lot.
* Tailor marketing strategies to targe those customers who are casual riders.
* Possibly do weekend deals on signing up for memberships on the weekend since most of the casual customers ride on the weekends.

#### Key Findings:
* Our casual customers take the most rides of the weekends. Conversely, our members customers take the most rides during the week.
* On average, our Subscribers take shorter rides than our Casual Customers.
* Members of both types prefer to ride bikes in the afternoon and at 5pm.

