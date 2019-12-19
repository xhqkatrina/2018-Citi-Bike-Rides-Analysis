# 2018 Citi Bike Rides Analysis

## Introduction
Like all the sharing systems we know, Airbnb, Uber etc., the Citi Bike is also a sharing system which is the network of bicycle rental stations intended for point-to-point transportation. The Citi Bike is also the largest bike sharing system in NYC, with 12000 bikes and 750 stations across Manhattan, Brooklyn and Queens. It’s a fast, healthy, sustainable and highly popular way to get around NYC.

In our project, we will mainly focus on two parts about Citi Bike Dataset. For the first part, we will focus on the general analysis about this dataset, including the analysis of Age, Gender, Usertype, the most popular routes or stations etc. In addition to analysis about the data, we will come up some recommendations based on the findings which we explore from the plots. For the second part, we will focus on and interactive visualization. Our shiny app shows more details about some of the questions we analyzed on the first part, displaying more geographical information and providing new insights.

## Data
Both raw data and tidy data are too large to upload onto Github. Please go to https://www.citibikenyc.com/system-data to download all trip records in 2018.

## Partial Results of Exploratory Data Analysis

### How many trips on each Month throughout the year?
<img src="https://github.com/xhqkatrina/2018-Citi-Bike-Rides-Analysis/blob/master/data/images/monthly_trip.PNG" width="512">

### How many trips in each hour of the day?
<img src="https://github.com/xhqkatrina/2018-Citi-Bike-Rides-Analysis/blob/master/data/images/hourly_trip.PNG" width="512">

### Weather impact on bike usage
<img src="https://github.com/xhqkatrina/2018-Citi-Bike-Rides-Analysis/blob/master/data/images/weather_impact.PNG" width="512">

## Interactive Component (R Shiny)
The interactive component allows users to visualize citi bike trip records on the map of New York City. The app presents information related to some of our previous analysis: how many trips there are in each hour, what the most popular stations/routes are etc. Since the dataset includes geographical information, users can get a better view through observing the map. In addition, we give users the option to view hourly map, which allows them to see the dynamic change throughout the day.

[Link to R Shiny App](https://xhqkatrina.shinyapps.io/5293_final_project/)

