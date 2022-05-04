# Geospatial PyDev
________

## DATA

**(1) NASA Fire Information for Resource Management Systems**

- Data Information

MODIS standard quality Thermal Anomalies / Fire locations processed by the University of Maryland with a 3-month lag and distributed by FIRMS. These standard data (MCD14ML) replace the NRT (MCD14DL) files when available.
Data is available from 01-01-2015 until 31-08-2021 (downloaded on Jan 28, 2022)

For more details please visit - [NASA FIRMS MODIS or VIIRS Fire/Hotspot Data Download](https://firms.modaps.eosdis.nasa.gov/download/Readme.txt)

- Data Citation and Disclaimer

NASA promotes the full and open sharing of all data with the research and applications
communities, private industry, academia, and the general public. Read the NASA Data and
Information Policy. 

- Citation
See: https://earthdata.nasa.gov/earth-observation-data/near-real-time/citation#ed-firms-citation 

**(2) ESRI have made available a ten class global land use/land cover (LULC) map for the year 2020 at 10 meter resolution available at this [link](https://www.arcgis.com/home/item.html?id=d6642f8a4f6d4685a24ae2dc0c73d4ac).**

## TASKS

NASA Fire Information dataset includes categories of fires that are not a result of agricultural practices as well. But for our analysis, we want to create a subset of this which gives the probability of a fire being caused by agricultural practices. The task for you is to use the ESRI LULC Map to propose a methodology and implementation for creating this subset. As this is an unsupervised model, we will not specificially be testing your code for evaluation metrics but on your approach and implementation. **The coding needs to be in PYTHON ONLY.**

The output of this task should be in a JSON format and should include the following keys - fireID, probability