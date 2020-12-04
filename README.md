# Benefits of natural habitat particularly woodland on childen's cognition and mental health

This 'Human Exposure' repository is created to provide transparent and publicly available data and code with regards to the manuscript called 'Benefits of natural habitat particularly woodland on children's cognition and mental health' published at ... .

This repository provides the three-tier natural habitat characterisation that is at the basis for developing an exposure assessment of natural habitat around each participant's home and school in the London metropolitan area. This includes:

* Layer 1: natural space
* Layer 2: green and blue space
* Layer 3: grassland and woodland

The natural habitat characterisation is based on publicly available data sources. NDVI maps were developed based on Sentinel-2 satellite data and are available using Google Earth Engine at earthengine.google.com. Buildings, surface water and tidal water data from the Ordnance Survey Open Map are available at ordnancesurvey.co.uk. LiDAR data from the Environment Agency are available at data.gov.uk. The natural habitat exposure data are not publicly available for data protection issues. To request access to the data, contact M. B. Toledano at m.toledano@imperial.ac.uk.

The repository also provides code for processing raw LiDAR data, creating environmental exposure variables and modelling our data. We used the available code in Python 3.7.3. and R 4.0.0 via RStudio using the packages brinla, ggplot2, ggpubr, R-INLA, MBA, raster, rgdal, sp and spdep60. The source code to compute NDVI from satellite data using Google Earth Engine is available at earthengine.google.com. 
