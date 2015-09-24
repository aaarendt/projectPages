# Exploration of software tools for geospatial analysis

Many modern data science problems require an understanding of a feature's spatial location. For example, Google, Amazon and many others have developed sophisticated algorithms to track the movement of products and people in time and space. However, equivalent toolkits for exploring environmental datasets, nearly all of which require an assessment of complex spatial relationships, have been slower to evolve. Traditionally, scientists have relied on commercial Geographic Information System (GIS) software, the most popular of which is ArcGIS. While this remains an important toolkit for geospatial investigations, it is not a software package available to all researchers on any platform. In this project, we are investigating a promising new set of open source toolkits, which, in combination with commercial software, can provide a wide range of new solutions to earth and ocean science, urban planning and other disciplines.

We are currently working on the following:

## New methods for slicing large gridded climate datasets:

Environmental researchers commonly need to access slices of array-oriented datasets for their analysis. For example, climate data are commonly distributed in large gridded file formats which individuals must then partition in order to obtain spatial subsets and/or temporal averages. At present, most researchers build loops to search through the grid stack in ways that tend to be slow, memory intensive and limiting to creative exploration of the data.

This project aims to investigate a suite of new software tools currently available to perform rapid analytics on array-oriented datasets. We are focusing on a new Python libraries called [xray] (http://xray.readthedocs.org/en/stable/) which extends [pandas] (http://pandas.pydata.org/) data structures to multiple dimensions. Used in combination with [dask] (http://dask.pydata.org/en/latest/), we are able to perform parallel computing on datasets too large for in-memory computation, but small enough for processing on a standard laptop. We also are investigating [geopandas] (http://geopandas.org/) as a way of enabling geospatial functionality within the pandas framework, as well as [Google Earth Engine] (https://earthengine.google.org) for cloud-based processing of climate and satellite imagery.

![array graphic](/arrayGraphic.jpg)

Our goal is to determine best practices for implementing the xray/dask libraries to analyze gridded climate data and hydrological runoff output associated with several ongoing research initiatives. In particular, we have just received [Azure for Research] (http://research.microsoft.com/en-us/projects/azure/cdi.aspx) support to explore the development of tools to address climate change. 

### Project participants:

*[Anthony Arendt] (http://psc.apl.uw.edu/people/investigators/anthony-arendt/)
*[Jake Vanderplas] (http://www.astro.washington.edu/users/vanderplas/research.html)
*[Ben Hudson] (http://psc.apl.uw.edu/people/post-docs/ben-hudson/) (Polar Science Center)

## Open source relational databases

[PostgreSQL] (http://www.postgresql.org/) is a popular enterprise level relational database. When combined with the [PostGIS] (http://postgis.net/) extension, this provides a powerful set of tools for handling geospatial data encoded using the vector data model (points, lines and polygons). This software combination can act as a backend to commercial GIS packages, and interfaces particularly well with the open source [QGIS] (http://www.qgis.org) package.

We are working to implement relation databases as a standard tool for environmental studies. As a prototype, we have developed an extensive database in support of the [ice2oceans] (https://csc.alaska.edu/projects/gulf-of-alaska-runoff) project funded by the USGS Alaska Climate Science Center. We are developing new ways to rapidly deploy and maintain these systems using cloud infrastructure.

![glaciers graphic](/glaciersGraphic.jpg)

### Project participants:

*[Anthony Arendt] (http://psc.apl.uw.edu/people/investigators/anthony-arendt/)
*[Christian Kienholz] (http://glaciers.gi.alaska.edu/people/kienholz) (University of Alaska Fairbanks)
 