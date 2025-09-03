# Spatio-Temporal Analysis of NO₂ Column Density in Delhi (2019-2024)
## Project Overview
This project provides a detailed spatio-temporal analysis of tropospheric Nitrogen Dioxide (NO₂) column number density over Delhi, India, for the summer months (March–June) between 2019 and 2024. The objective is to identify and visualize pollution trends and hotspots across the region over a six-year period.

The analysis leverages satellite data from the Copernicus Sentinel-5P mission, accessed via the Google Earth Engine (GEE) API. The notebook demonstrates the full workflow, from data acquisition and preprocessing to advanced data visualization, including generating both static subplots and dynamic animations.

## Key Features
1. Data Acquisition: Fetches Sentinel-5P L3_NO2 data directly from Google Earth Engine.
2. Spatio-Temporal Filtering: Narrows down the data to the specific geographical boundary of Delhi and filters it for the summer months (March to June) annually.
3. Data Processing: Calculates the mean NO₂ density for each year and clips the data precisely to Delhi's state and district boundaries using shapefiles.
4. Visualization: Creates insightful spatial plots to compare annual pollution levels and generates an animation to visualize the temporal evolution of NO₂ hotspots.

## Technologies Used
- Python
- Google Earth Engine (ee) for satellite data access
- wxee & xarray for processing GEE data
- GeoPandas & rioxarray for geospatial operations
- Matplotlib for plotting and animations
