# Hurricane-and-Tropical-Storm-Visualization-Analysis

A project for QGIS for hurricanes and tropical storms affecting insurance policy holders in the United States.  

This objective is achieved by using several sets of various data to create a forcast map.  

# Data used:
    - Live and historic storm data to create visualized storm path and 'cone of uncertainty.'
        - https://www.nhc.noaa.gov/data/
        - https://www.data.gov/disasters/hurricanes/
        
    - United States Census data for population size/density, ZIP code boundaries.
        - https://www2.census.gov/geo/tiger/TIGER2017/ZCTA5/tl_2017_us_zcta510.zip
        
    - Sample health insurance policy holder information. 
        - https://data.healthcare.gov/

## Installation

1. Clone this repository somewhere safe on your computer
2. Download the latest `data.zip`: [6 July 2018](https://spatialgisdbinterns20614.file.core.windows.net/hurricanes/data.zip?st=2018-07-06T18%3A29%3A02Z&se=2019-07-07T18%3A29%3A00Z&sp=rl&sv=2017-07-29&sr=f&sig=0h43yLBEUNyveT%2B7J0kum4DHZbo89Q0cGgzjkFFgZhI%3D)
3. Extract `data.zip` into your project directory. You should end up with a hierarchy matching `/project/data/archive`
4. Open `project.qgs` using QGIS

## Latest Verified Environment
    QGIS 3.2.0-Bonn
    Compiled against Qt 5.9.3, GDAL/OGR 2.2.4, GEOS 3.6.2-CAPI-1.10.2
    macOS High Sierra 10.13.5 
