## Choose the dataset
City of Chicago dataset.
- [Crimes rate from year 2001](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)
- [Visitors in a library of chicago from 2014](https://data.cityofchicago.org/Education/Libraries-2014-Visitors-by-Location/si8n-dg3u)
- [Visitors in a library of chicago from 2013](https://data.cityofchicago.org/Education/Libraries-2013-Visitors-by-Location/x74m-smqb/data)
- [Visitors in a library of chicago from 2012](https://data.cityofchicago.org/Education/Libraries-2012-Visitors-by-Location/zh3n-jtnt/data)
- [Annual Taxpayer Location Address List 2014](https://data.cityofchicago.org/Community-Economic-Development/Annual-Taxpayer-Location-Address-List-2014/kukh-c9wt/data)
- [RedLight camera violations](https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37)
- [Libraries - Locations, Hours and Contact Information](https://data.cityofchicago.org/Education/Libraries-Locations-Hours-and-Contact-Information/x8fc-8rcq) 

> Try to write data and what we are analyzing in a same number here
## What we want to analyze or what aspect we should analyze
- No of crimes in a mapped to the addresses of chicago
- No of visitors in library of chicago from 2014, 2013 and 2012
- No of red light violations mapped with area of intersection
- mappping the library with the timings they are open(not so sure about this but it might be good)

## What technology we will be using and why
Pypark for analyzing the dataset considering the better in-memory RDD computation technique

## What we want to preprocess from the data
Drop out the columns which are less significant 
