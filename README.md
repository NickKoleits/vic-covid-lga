# COVID-19 by Victorian LGAs Visualisation
---

## Background

Australia has faired well compared to other developed nations in relation to the outbreak of COVID-19. However, within Australia, Victoria has had the largest outbreak of cases among all states - particularily Metropolitan Melbourne. Being a Melbournian myself, I've had a little extra spare time on my hands with the second round of stage 4 restrictions imposed on 3 August 2020. With this spare time, I decided to make an animated map of Greater Melbourne Local Government Areas (LGAs) to visualise the spread of COVID-19 cases in Greater Melbourne.

This project involves web-scarping of daily COVID-19 cases for Victorian LGAs to generate a time-lapse chloropleth maps to visualise COVID-19 cases to highlight to visually represent:
1. active cases; and
2. cumulative cases.

![Active cases](gif/active_cases.gif)

## Where was the data sourced?

1. The COVID-19 data was sourced from https://covidlive.com.au/. 
2. Shapefile to create map base layer was sourced from the Australian Bureau of Statistics (ABS): https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202016?OpenDocument

A big thank you to Benjamin Cooley for creating a detailed blog post about making interactive maps using Pandas and Matplotlib. Click [here](https://towardsdatascience.com/lets-make-a-map-using-geopandas-pandas-and-matplotlib-to-make-a-chloropleth-map-dddc31c1983d) to see the original post.


## What does this repo contain?

1. [Web-scraping and visualisation notebook](https://github.com/NickKoleits/vic-covid-lga/blob/master/notebooks/Melbourne_COVID_cases.ipynb)
2. [Active cases GIF](https://github.com/NickKoleits/vic-covid-lga/blob/master/gif/active_cases.gif)
3. [Cumulative cases GIF](https://github.com/NickKoleits/vic-covid-lga/blob/master/gif/cumulative_cases.gif)

## Contact
Feel free to reach out if you have any queries\n
e: nkoleits@gmail.com
