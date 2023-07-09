# Land-Use-Analysis_Abuja
GIS analysis of 2017 to 2022 Sentinel-2 Land use map for Abuja, Nigeria 

# Table of Contents
1. [Overview](#Overview)
2. [About](#About)
3. [Dataframe Structure](#Dataframe-Structure)
4. [Data Dictionary](#Data-Dictionary)
5. [Limitation](#Limitation)
6. [Credits(Attribution)](#Credits(Attribution))
7. [References](#References)


 # Overview
In this project, the data obtained displays a map of land use/land cover (LULC) derived from [ESA Sentinel-2 imagery](https://livingatlas.arcgis.com/landcoverexplorer/#mapCenter=-83.21%2C34.332%2C4&mode=step&timeExtent=2017%2C2021&year=2017&downloadMode=true) at 10m resolution. Each year is generated with Impact Observatory’s deep learning AI land classification model, trained using billions of human-labeled image pixels from the National Geographic Society. The maps are produced by applying this model to the Sentinel-2 Level-2A image collection on Microsoft’s Planetary Computer, processing over 400,000 Earth observations per year.

 





# Limitation
Land use focus does not provide the spatial detail of a land cover map. As such, for the built area classification, yards, parks, and groves will appear as built areas rather than trees or rangeland classes.
The year 2017 has a land cover class assigned for every pixel, but its class is based upon fewer images than the other years. The years 2018-2022 are based upon a more complete set of imagery. For this reason, the year 2017 may have less accurate land cover class assignments than the years 2018-2022.


# Credit(Attribution)
Training data for this project makes use of the National Geographic Society Dynamic World training dataset, produced for the Dynamic World Project by the National Geographic Society in partnership with Google and the World Resources Institute.

Impact Observatory, Microsoft, and Esri.
(https://ic.imagery1.arcgis.com/arcgis/rest/services/Sentinel2_10m_LandCover/ImageServer)
This work is licensed under a Creative Commons by Attribution (CC BY 4.0) license.
[View License Deed](https://creativecommons.org/licenses/by/4.0/)| [View Legal Code](https://creativecommons.org/licenses/by/4.0/legalcode)
