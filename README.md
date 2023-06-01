# Geo for Good Summit Examples

### Example 1: Land-use change in Madre de Dios, Peru (peru_land_use_change)
This folder contains two files. The first (LandUse_Map_MadredeDios.pdf) is a map of the Madre de Dios region of Peru in 2020, with each 1km grid cell categorized by land-use type (data from MapBiomas). The second is a figure I made showing district-level trajectories of land-use change in the region over time, using the same data as the first image but from annual snapshots from 2000 -- 2020. I used Google Earth Engine to calculate areas of the various land-use categories over time for each district. This data serves as predictor variables for a project that aims to link land-use change to vector-borne disease throughout the region.

### Example 2: Species distribution modeling for disease hosts (climate_land_use_rasters).
This folder shows climate and land-use rasters that I accessed and processed using Google Earth Engine. I use them as predictors for a set of species distribution models. Specifically, these models help us predict areas with habitat suitable for non-human species. In disease applications, these non-human species are organisms that can facilitate disease transmission (such as mosquitoes for malaria, or snails for schistosomiasis). These are maps of environmental covariates across geographic scales (national, Minas Gerais, and São Paulo state). Bioclimatic variables (i.e. temperature and precipitation) are colored in orange, soil-related variables in blue, and land-use/land-cover variables in green. 
A) Temperature seasonality (standard deviation of the monthly mean temperatures) 
B) Mean daily temperature of the coldest quarter
C) Mean monthly precipitation of the wettest quarter 
D) Mean monthly precipitation amount of the driest quarter 
E) Soil clay percentage
F) Height above nearest drainage
G) Soil pH
H) Soil water percentage
I) Proportion of temporary crop cover 
J) Distance to high population density
