# Houston Texas Blackout Analysis 

In February 2021, Texas experienced a winter storm with abnormally cold temperatures. This storm wreaked havoc across the state, causing pipes to freeze, crops to fail, and, most visibly, massive power outages. Houston, Texas, experienced a particularly severe blackout due to many homes being connected to the same power grids, which were damaged by the storm. This analysis visualizes the outage by comparing light intensities in Houston on February 7, 2021 (before the storm) and February 16, 2021 (after the storm). Additionally, it maps buildings and census tracts affected by the outage. Then, explores potential environmental injustices by comparing median income between census tracts that experienced and did not experience a blackout.

### Repository Structure
```
├── data
│   ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb
│   ├── gis_osm_buildings_a_free_1.gpkg
│   ├── gis_osm_roads_free_1.gpkg
│   └── VNP46A1
│       ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif
│       ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif
│       ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif
│       └── VNP46A1.A2021047.h08v06.001.2021048091105.tif
├── eds-223-texas-blackout.Rproj
├── README.md
├── texas_blackout.pdf
└── texas_blackout.qmd
```
### Folder Descriptions: 

/data:
* ACS_2019_5YR_TRACT_48_TEXAS.gdb: Census tract geometry and attribute data for Texas.
* gis_osm_buildings_a_free_1.gpkg: Houston building geometry and attribute data
* gis_osm_roads_free_1.gpkg: Houston highway geometry data
* VNP46A1: VIIRS tiles containing satelite images of light intensity for an area that overlaps Houston

/eds-223-texas-blackout.Rproj
* R project space for analysis
  
/texas_blackout.pdf
* Output pdf with code and figures

/texas_blackout.qmd
* Quarto document containing code and scripts for analysis

### Author: [Richard Montes Lemus](richardmonteslemus.github.io)

### Acknowledgement: Bren School Master of Environmental Data Science EDS 223 homework 2 coursework materials

### Language: R 

| Citation |
|---------------------|
| Lee CC, Maron M, Mostafavi A. Community-scale big data reveals disparate impacts of the Texas winter storm of 2021 and its managed power outage. Humanit Soc Sci Commun. 2022;9(1):335. doi: 10.1057/s41599-022-01353-8. Epub 2022 Sep 24. PMID: 36187845; PMCID: PMC9510185. https://pubmed.ncbi.nlm.nih.gov/36187845/ 
| OpenStreetMap contributors (2025). OpenStreetMap [Data set]. OpenStreetMap Foundation. Available as open data under the Open Data Commons Open Database License (ODbL) at <https://www.openstreetmap.org> |
|U.S. Census Bureau. (2020). TIGER/Line Shapefiles and American Community Survey 2019 (5-Year-Estimates), Texas-Census Tract Level (ACS_2019_5YR_TRACT_48_TEXAS) [Data set]. U.S. Department of Commerce. available at https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-data.html |
