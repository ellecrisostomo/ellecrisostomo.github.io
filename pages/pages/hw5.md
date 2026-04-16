---
layout: page
title: UFO Sightings Visualization
permalink: /hw5/
---

## UFO Sightings Over Time


<iframe src="/chart1.html" width="600" height="400"></iframe>


Chart 1 displays the number of UFO sightings over time using a line chart. The x-axis encodes year as a measurement of time as a quantitative variable, while the y-axis represents the number of sightings recorded during that year. After first creating a datetime column, I then converted it and grouped the dataset entries by 'year', which allowed for a clear depiction of the time-based trends and insights found in the data.  As I chose to use time for the basis of my visualization, a line graph was chosen as it clearly depicts how values, in this case, the number of UFO sightings, change over a period of time. I did not choose any extra color schemes for this graph because the nature of the graph itself is much better understood when the line is kept simple, and with line graphs, it is important that it is not overcomplicated to distract the audience from the trends conveyed. 

## UFO Shapes by State


<iframe src="/chart2.html" width="600" height="400"></iframe>


Chart 2 shows the number of sightings of each UFO shape using a bar chart. The x-axis encodes shape as a categorical variable, while the y-axis represents the number of sightings per shape that were recorded within the data set. Additionally, there is a dropdown included in this visualization to filter the data by state, so only the data for one state appears at a time. To create this chart, I began by removing any missing values within the data and standardized text fields so that I was able to then perform analysis. Incorporating the dropdown allows the audience to explore how geographic location and differences in regions might shape the distributions of reported UFO shapes. Being able to filter by state, the visualization allows users to explore and further investigate how UFOs might take on different forms depending on where they are, geographically, in the country.

## Links

<a href="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv">The Data</a>

<br>

<a href="https://github.com/ellecrisostomo/ellecrisostomo.github.io/blob/main/IS445-Homework5.ipynb">The Analysis</a>
