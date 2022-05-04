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

NASA Fire Information dataset includes categories of fires that are not a result of agricultural practices as well. But for this analysis, we want to create a subset of this which gives the probability of a fire being caused by agricultural practices. The task uses the ESRI LULC Map to propose a methodology and implementation for creating this subset using an unsupervised model. 

The output of this task is in a JSON format and includes the following keys - fireID, probability

## References

- [Stubble burning in Northern India](https://earthobservatory.nasa.gov/images/84680/stubble-burning-in-northern-india)
- [Active Fire Data - NASA | LANCE | FIRMS](https://firms.modaps.eosdis.nasa.gov/active_fire/)
- [NASA Firms Data Download](https://firms.modaps.eosdis.nasa.gov/download/Readme.txt)
- [NASA Fires Visualization for Telangana](https://public.flourish.studio/visualisation/8561801/)
- [Visualizing Climate and Loss: Crop Residue Burning in India](https://histecon.fas.harvard.edu/climate-loss/crops/index.html)
- [Esri 2020 Land Cover - Overview](https://www.arcgis.com/home/item.html?id=d6642f8a4f6d4685a24ae2dc0c73d4ac)
