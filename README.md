# UFO Website

## Overview

The goal of this project was to create a functioning website that would allow the end user to search and filter through
a larghe data set of UFO sightings and have it displayed in a table for easy consumption by the user. The website was built using
Bootstrap 4 framework, using a CSS style sheet and running the script to filter our data set using JavaScript.

## Results

When an indiviual first visits the website, all filtered searches are cleared and the table shows every single UFO sighting
data point in the database.
![alt text](https://github.com/jseverin1984/UFOs/blob/main/Resources/cleared_search_filter.png "cleared search field")

When the user would like to make the UFO sightings more managable to look at or want to find specific sightings, they can
chose from five different filter options.
![alt text](https://github.com/jseverin1984/UFOs/blob/main/Resources/filter_options.png "filter options")

As the user enters certain criteria into the search filters, the table automatically updates with the information they are
looking for. Below will be three pictures depicting how the table updates as you add filters.

First, we will fiter by selecting a specific date, 1/1/2010.
![alt text](https://github.com/jseverin1984/UFOs/blob/main/Resources/filter_date.png "date filter")

Second, we will add to the filter criteria a city, el cajon.
![alt text](https://github.com/jseverin1984/UFOs/blob/main/Resources/filter_date_city.png "date city filter")

Lastly, a third filter, shape (triangle) will be added.
![alt text](https://github.com/jseverin1984/UFOs/blob/main/Resources/filter_date_city_shape.png "date city shape filter")


## Summary

The main drawback to this website is that its data set to build the searchable table from is static. It will never be updated
unless Dana manually adds to the data set. So, one recommendation for further development of this website would be to host the data
in a database that can be automatically written to as new UFO sightings are reported. Ever expanding the users ability to stay updated
with the latest information. A second reommendation would be the ability to have more than one parameter within each filter.  So you
could filter by a date range, instead of just a single date. Or, look at UFO sightings from multiple states.

