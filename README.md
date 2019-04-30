# Texas Census to BTTN Conflation

Notebook Author: Mark Egge (mark@eateggs.com)

This example notebook demonstrates the use of Jupyter Notebook, PostgreSQL + PostGIS, and Python to spatially join census data to Texas Department of Transportation's Bicycle Tourism Trails (BTT) Example Network.

## Project Goal

Determine the income distribution of households living within 5 km of TxDOT's Bicycle Tourism Trail Network (BTTN).


## Data Sources

* Bicycle Tourism Trails (BTT) Example Network Shapefile (EPSG:3857)
* ACS 5-Year Estimates 2012 – 2017 Table B19001 "HOUSEHOLD INCOME IN THE PAST 12 MONTHS IN 2017 INFLATION-ADJUSTED DOLLARS" (EPSG:4326)
* ACS 2017 TIGER/Line Shapefile - Block Groups (EPSG:4269)

## Requirements

* PostgreSQL with PostGIS extension installed
* Python 3, matplotlib, pandas
* [SQL Extension for Jupyter Notebook](https://github.com/catherinedevlin/ipython-sql) (recommended)