## Tools for rapid analysis of gridded environmental datasets

Environmental researchers commonly need to access slices of array-oriented datasets for their analysis. For example, climate data are commonly distributed in large gridded file formats which individuals must then partition in order to obtain spatial subsets and/or temporal averages. This often requires development of code that loops through the grid stack in ways that tend to be slow, memory intensive and limiting to creative exploration of the data.

This project aims to investigate a suite of new software tools currently available to perform rapid analytics on array-oriented datasets. We are focusing on a new Python libraries called [xray] (http://xray.readthedocs.org/en/stable/) which extends [pandas] (http://pandas.pydata.org/) data structures to multiple dimensions. Used in combination with [dask] (http://dask.pydata.org/en/latest/), we are able to perform parallel computing on datasets too large for in-memory computation, but small enough for processing on a standard laptop. 

Our goal is to determine best practices for implementing the xray/dask libraries to analyze gridded climate data and hydrological runoff output associated with the ice2oceans research objectives. 


## Project participants:

-[Anthony Arendt] (http://psc.apl.uw.edu/people/investigators/anthony-arendt/)
-[Jake Vanderplas] (http://www.astro.washington.edu/users/vanderplas/research.html)

 