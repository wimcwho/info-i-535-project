# info-i-535-project

# Title:
Distributed K-Means and Image Clustering

# Description: 
This project aims to implement a distributed K-Means class utilizing PySpark in order to do clustering on datasets thats are too large to fit inside the memory of a single machine, and to operate faster than doing single machine on disk computations. The project then operates on both the iris dataset from Sci-Kit Learn and weather images from Kaggle.

# Data:
The data for this project is sourced from Kaggle (https://www.kaggle.com/datasets/jehanbhathena/weather-dataset). The original source for this dataset is provided by Haixia Xiao from the Nanjing Joint Institute for Atmospheric Sciences, deposited to dataverse.harvard.edu [1]. The metadata listed in this repository is sourced from this initial repository from Harvard Dataverse. The original data was then updated by Jehan Bhathena (@jehanbhathena on Kaggle) by removing images that were deemed as fake.

# Use: 
This project can be operated by importing the Jupyter notebook and the archive.zip data file into one folder on a cluster that supports PySpark distributed programming. 

# References:
[1] Haixia Xiao. Weather phenomenon database (WEAPD), 2021.
