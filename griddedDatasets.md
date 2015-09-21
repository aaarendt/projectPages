## Tools for rapid analysis of gridded environmental datasets

Environmental researchers commonly need to access slices of array-oriented datasets for their analysis. For example, climate data are commonly distributed in large gridded file formats which individuals must then partition in order to obtain spatial subsets and/or temporal averages. This often requires development of code to loop through the grid stack which can be slow and memory intensive.

This project aims to investigate a suite of new software tools currently available to perform rapid analytics on array-oriented datasets. We are focusing on a set of new Python libraries including [xray] (http://xray.readthedocs.org/en/stable/).