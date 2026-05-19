# Project_GEO876 #

This project accesses live data from the NASA Fire Information for Resource Management System (FIRMS) API and visualizes them on an interactive map. This step-by-step approach first checks the available data, collects the data for three VIIRS-sensors, performs some data cleaning and visualization tests, before plotting the final data in an interactive map.

Each point represents a potential wildfire hotspot. The points are colored according to the fire intensity in MW. More information like the date of recording can be accessed through the tooltip.

<h2>Data acquisition:</h2>
The live data is accessible on https://firms.modaps.eosdis.nasa.gov/api/. To access the data, a map key has to be generated on the FIRMS website: https://firms.modaps.eosdis.nasa.gov/api/map_key/. NASA provides some example code, which helped to set up and access the data.
  
This project uses data from all three viirs sensors. A detailed description of the attributes can be downloaded on the FIRMS website.

<h2>Requirements</h2>

This project was made with python 3.12 and JupyterLab.  
This project requires the following libraries:  
**Data analysis:** `pandas`, `numpy`  
**Geographic data and basemap:** `geopandas`, `contextily`  
**Visualization:** `matplotlib`, `folium`, `branca`

Instead of installing all packages you can use the provided environment.yml  
To run all code smoothly, please make sure to keep and use the same folder structure as provided in this repository. The final map is a html file and can be opend in your browser.



