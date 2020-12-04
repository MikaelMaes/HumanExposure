## Technical specifications

This section of the repository provides the three-tier natural habitat characterisation that is at the basis for developing an exposure assessment of natural habitat around each participant's home and school in the London metropolitan area. This includes:

* Layer 1: natural space
* Layer 2: green and blue space
* Layer 3: grassland and woodland

When importing layers into Geographic Information Systems, 
All layers are projected in British National Grid / OSGB 1936. Layer 1 and 2 are currently provided here as a .jpeg file. Due to file size, layer 3 is available on request from M. J. A. M. at mikael.maes.16@ucl.ac.uk.

```
# R code to project spatial data into OSGB 1936
"+proj=tmerc +lat_0=49 +lon_0=-2 +k=0.9996012717 +x_0=400000 +y_0=-100000 +datum=OSGB36 +units=m +no_defs +ellps=airy +towgs84=446.448,-125.157,542.060,0.1502,0.2470,0.8421,-20.4894"
```
