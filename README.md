# leaflet-challenge

https://github.com/sanjchip/leaflet-challenge/blob/f2e3f2f15b6cedb517d31f5ef96bbd244106f91e/Images/1-Logo.png


**Details**
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 

A visualization is done of the USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.



## Leaflet Part 1: Earthquake Visualization


The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an [external site](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and choose a dataset to visualize


https://github.com/sanjchip/leaflet-challenge/blob/f2e3f2f15b6cedb517d31f5ef96bbd244106f91e/Images/3-Data.png

When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

https://github.com/sanjchip/leaflet-challenge/blob/f2e3f2f15b6cedb517d31f5ef96bbd244106f91e/Images/4-JSON.png


You can download the raw file from https://github.com/sanjchip/leaflet-challenge/tree/2c90dc08073235281521b0ce29c7f314a8c4bcbe/Leaflet-Part-1
and change the "url" to any GeoJSON links you would like to get data from 

https://github.com/sanjchip/leaflet-challenge/blob/f2e3f2f15b6cedb517d31f5ef96bbd244106f91e/Images/1.png

## Leaflet Part 2: Earthquake Visualization

Second dataset is to illustrate the relationship between tectonic plates and seismic activity. You will can this dataset and visualize it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplatesLinks 


https://github.com/sanjchip/leaflet-challenge/blob/f2e3f2f15b6cedb517d31f5ef96bbd244106f91e/Images/2%20.png

Just replace the "url_plates" with any GeoJSON of your liking 
After downloading https://github.com/sanjchip/leaflet-challenge/tree/f2e3f2f15b6cedb517d31f5ef96bbd244106f91e/Leaflet-Part-2


**Resources**

- Leaflet
- HTML
- CSS
- D3
- JavaScript

**References**

Dataset created by the United States Geological SurveyLinks [external site](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)