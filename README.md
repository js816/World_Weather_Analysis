# PlanMyTrip App 

## Overview of Project

The purpose of this project was to help design the PlanMyTrip app to allow our customers to make better informed decisions about travel destinations and to easily access data about various cities.

## WeatherPy

As part of this project, coding was implemented to leverage OpenWeather APIs to access real-time weather data for nearly 700 world cities.  We chose to focus on key weather data.  Conditions that we extract from the APIs are:  high temperature, humidity, % cloudiness, wind speed, and current description.  This last variable includes descriptions such as:  scattered clouds, clear sky, light rain, and fog.  A portion of the data is shown below.

![Table](https://user-images.githubusercontent.com/82730954/121416019-f3725600-c92d-11eb-92bd-1b3f83042494.PNG)


As part of this portion of the project, I also developed some visualizations that highlight the relationship (or lack of a relationship) between latitude and weather factors such as temperature, humidity, and cloudiness.  These were presented to local students to help them understand how various factors impact weather across the world and how data and statistics can investigate these questions.  Sample graphs are shown below.

![Weather_chart1](https://user-images.githubusercontent.com/82730954/121416059-fec58180-c92d-11eb-8726-aea78a4cbb70.png)

![Weather_chart2](https://user-images.githubusercontent.com/82730954/121416063-008f4500-c92e-11eb-967d-8424a97054c2.png)


## VacationPy

### Vacation Search

Once the weather data was gathered, coding was developed to request a range of temperatures from our customer.  The high temperature was then filtered so only cities within the range selected by the customer were shown.  Google Maps API were then leveraged to find hotels near the city.  Google Maps where then created to show the filtered cities.  Each city has a marker and if clicked by the user, the marker displays the nearest hotel, the city name, the country, and the current high temperature and weather conditions.  Sample maps are shown below.

![US_map](https://user-images.githubusercontent.com/82730954/121416130-11d85180-c92e-11eb-8b48-794ecd3d4533.png)

![World_map](https://user-images.githubusercontent.com/82730954/121416148-16046f00-c92e-11eb-911f-8b83ca9edbcb.png)


### Vacation Itinerary

The final portion of this part of the project was to develop an itinerary map that allows our customers to select multiple cities and see routing between the cities.  An example of the itinerary map is shown below.

![Spain_itinerary](https://user-images.githubusercontent.com/82730954/121416188-21579a80-c92e-11eb-8f45-c94bafb3e780.png)


## Summary

Providing these additional offerings to our customers allow them to be more intentional about their travel plans and have a more visual experience.

### Ideas for future improvements

There are several opportunities for future enhancements to make PlanMyTrip even better.  

We could offer a more robust feature set such as the ability to examine historical weather and future predictions.  This would give our customers a better view of the bigger picture of weather conditions in various areas.

We could also allow customers to select other weather factors when filtering cities.  Also filtering on humidity or feels like temperature, for example, could allow customers to fine tune their requests.

Once the cities are presented, we could offer customers a variety of lodging options, perhaps even developing partnerships with key brands.

We would also have the opportunity to feature other nearby locations such as restaurants, attractions, and national parks to name just a few.

For determining directions, we could provide various options including walking, bicycling, driving, and mass transit.  This customization could be especially appealing to several of our customer segments.

Additionally, since cell coverage can be spotty in some areas or customers may intentionally unplug during their vacation, we could allow the printing of directions, selected hotel, confirmation numbers, etc., in one package so they have easy access to all key information.
