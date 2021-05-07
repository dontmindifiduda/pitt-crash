# Pittsburgh Crash Categorical Data Clustering Using K-Modes

![Pittsburgh Car Crashes (2009-2019)](https://github.com/dontmindifiduda/pitt-crash/blob/main/images/pitt_all_crashes.png)

The notebooks contained in this repository analyze crash data from automobile accidents reported in the City of Pittsburgh from 2009-2019. The data used for this analysis was provided by the Western Pennsylvania Regional Data Center and can be found at the following link:  [https://data.wprdc.org/dataset/allegheny-county-crash-data](https://data.wprdc.org/dataset/allegheny-county-crash-data). A data dictionary containing descriptions of each of the variables included in this dataset can be found here:  [https://data.wprdc.org/dataset/allegheny-county-crash-data/resource/4df9a3c6-34c1-45a5-936e-80758f9f38a5](https://data.wprdc.org/dataset/allegheny-county-crash-data/resource/4df9a3c6-34c1-45a5-936e-80758f9f38a5).


## pittsburgh-crash-categorical-clustering.ipynb
This notebook contains code that applies k-modes clustering to a filtered version of the raw dataset. The raw dataset includes records of over 121,000 car accidents in Allegheny County between 2004 and 2019. The filtered dataset limits the analysis to over 41,000 crashes occurring within the City of Pittsburgh between 2009-2019. Numerical features and features identified as having low importance were removed from the dataset. K-modes clustering was applied to categorical features in the dataset, and each observed accident was assigned to a cluster. 

Using the clusters assigned by k-modes, an exploratory data analysis was performed using data grouped by cluster. Clustering the dataset divides it into separate categories of accidents, and this analysis provides information about how the groups differ from one another. Plots of the geographic location of each crash were also generated for each cluster. These plots can be used to visually identify areas of increased crash density. Future analysis will include further clustering of geographical data using the clusters assigned by k-modes to identify locations of increased risk associated with specific categories of accidents. 


A Medium article providing a more detailed description of this analysis can be found here:  . 