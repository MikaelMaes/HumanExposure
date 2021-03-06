# Benefit of woodland and other natural environments for adolescents' cognition and mental health

This repository is created to provide transparent and publicly available data and code with regards to the manuscript called 'Benefit of woodland and other natural environments for adolescents' cognition and mental health'. More details about the manuscript will be available upon publication.

This repository provides the three-tier natural environment characterisation that is at the basis for developing an exposure assessment of natural environment types around each participant's home and school in the London metropolitan area. This includes:

* Layer 1: natural space
* Layer 2: green and blue space
* Layer 3: grassland and woodland

The natural environment characterisation is based on publicly available data sources. NDVI maps were developed based on Sentinel-2 satellite data and are available using Google Earth Engine at earthengine.google.com. Buildings, surface water and tidal water data from the Ordnance Survey Open Map are available at ordnancesurvey.co.uk. LiDAR data from the Environment Agency are available at data.gov.uk. The natural environment exposure data are not publicly available for data protection issues. To request access to the data, contact M. B. Toledano at m.toledano@imperial.ac.uk.

The repository also provides custom code for processing raw LiDAR data, creating environmental exposure variables and modelling our data. 

## Requirements

The data and custom code provided in this repository has been used within the following software:

* Python 3.7.3.
* ArcGIS 10.7
* R 4.0.0 (via RStudio using the packages brinla, ggplot2, ggpubr, R-INLA, MBA, raster, rgdal, sp and spdep60)

The source code to compute NDVI from satellite data using Google Earth Engine is available at earthengine.google.com.
