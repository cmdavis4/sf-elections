# Analysis of San Francisco's November 2016 Election Results

This repository contains analysis I have conducted on publicly available data regarding the November 2016 elections in San Francisco, coupled with some demographic data taken from the 2010 Bay Area Census. Most of the analysis is contained [here](./election_analysis.md). The scripts for the data pre-processing and the creation of an ArcGIS geodatabase are contained in [this IPython notebook](./geodatabase_from_source_data.ipynb).

### Data sources
* **2010 Census block lines**: https://data.sfgov.org/Geographic-Locations-and-Boundaries/Census-2010-Blocks-for-San-Francisco/2uzy-uv2r
* **2010 Bay Area Census demographic data by block**: http://www.bayareacensus.ca.gov/small/small.htm, specifically http://www.bayareacensus.ca.gov/small/2010_Pop_Block_County.xls (note: the shapefile for this data is broken, which is why I used the .xls file and manually spatially joined it)  
* **San Francisco precinct lines**: http://sfgov.org/elections/district-citywide-maps, specifically http://sfgov.org/elections/sites/default/files/2012lines.zip  
* **San Francisco November 2016 election results**: http://www.sfelections.org/results/20161108/#english_detail, specifically http://www.sfelections.org/results/20161108/data/20161206/20161206_sov.xlsx