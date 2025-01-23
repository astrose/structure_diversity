# structure_diversity
Code used in published work (DOI: 10.1002.ece3.70907).
This contains the code for St. Rose A., and Naithani K.J.2025. Unraveling the influence of structural complexity, environmental, and geographic factors on multi-trophic biodiversity in forested landscapes.

00 = Sourcing Data 
01 = Data Processing 
02 = Statistical Analysis

00.1 Contains code for downloading species data

00.2 Contains code for downloading structural data

01.1 Contains the processing information for the bird, beetle, and plant diversity. This includes pulling the data from the NEON data portal using neonUtilities packages, and also obtaining the diversity indices, using various packages.

01.2 Contains the DTM, DSM, CHM data processing. This includes merging AOP NEON data (code from Hass, B.'s NEON Tutorial) to represent the entire site and obtaining complexity metrics from rasters.

02.1 Contains the code for the species accumulation for every site by bird, plant, beetle, and combined.

02.2 Contains the code used to create novel multitrophic diversity index.

02.3 Contains the code for the correlation plot.

02.4 Contains the code for the NMDS and PERMANOVA.

02.51 Contains the code for built rf models and cross validation

02.521 Contains the code for built lm models and cross validation

02.522 Contains the code for built plm models and cross validation

We incorporated code from:

Adam, M. (2021). admahood/neondiveRsity: Added betadiversity and dissolve_years options (v1.2.5). Zenodo. https://doi.org/10.5281/zenodo.5261104

Hass, B., NEON (National Ecological Observatory Network)]. Data Tutorial: Merging AOP l3 Tiles in R into Full-Site Rasters. https://www.neonscience.org/resources/learning-hub/tutorials/merge-aop-raster-data (accessed: 1/27/2023).
