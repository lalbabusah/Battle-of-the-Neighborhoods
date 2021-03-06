## Table of contents
* [Introduction: Business Problem](#introduction)
* [Data Acquisition](#Data_Acquisition)
* [Data Wrangling](#Data_Wrangling)
* [Data Exploration](#Data_Exploration)
* [Model Development](#Model_Development)

## Introduction
In this project, compare the neighborhoods of Toronto. Since there are lots of venues in neighborhoods of Toronto, try to detect which type of venues are more common in Neighborhoods.

Specifically, this report will be targeted to stakeholders interested in finding which venues are more common or not in the neighborhoods of Toronto.

Use data science to generate a few most promising neighborhoods based on these criteria. The advantages of each area will then be clearly expressed so that the best possible final venue can be chosen by stakeholders.

## Data Acquisition
Based on definition of our problem, factors that will influence our decission are:
* Number of different types of venues in the neighborhood of Toronto.
* Venues which are more common in the neighborhoods of Toronto.

Following data sources will be needed for analysis of Neighborhoods of Toronto:
* For all the information I need to explore and cluster the neighborhoods in Toronto a Wikipedia page exists, here is the link: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M.
* For scraping the table, I can simply use pandas to read the table into a pandas dataframe.
* For the geographical coordinates of each postal code, read a csv file (https://cocl.us/Geospatial_data) using pandas dataframe.
* Explore the neighborhoods and segment them using Foursquare API.
