# About the Author
Kimberly Staudt is a graduate student pursuing Data Science at Mercyhurst University.\
Email:kstaud85@lakers.mercyhurst.edu\
License: None

This is a data visualization project for the course DATA 550.
This project utilizes data from the BrendaSo's kernal "U.S Pollution Data".
This project seeks to analyze the levels of pollutants by U.S. state. 
Bokeh plots are created as an html outfile. A screenshot of the output is provided. 

The CSV file for this dataset is too large to be uploaded to GitHub, it can be downloaded here:\
https://www.kaggle.com/sogun3/uspollution/data


# Repository Contents
1.Readme \
2.Jupyter Notebook file (cleaning, plotting, visualizations)\
3.bokeh_plot.png (bokeh plot)\
4.barchart1.png\
5.barchart2.png\
6.barchart2.png\
7.barchart3.png\
8.barchart4.png\
9.bargraph.png\
10.scatter.png\
11.table.png




# Table of Contents
I.Purpose\
II. About the Data\
III.Packages\
IV.Project Explanation\
V.Conclusion\
VI.Related Efforts 

# I. Purpose

The purpose of this project is to find, clean, plot, and visualize the pollution data set.

# II. About the Data

The data consists of 11 columns and 436876 rows (after cleaning). 
Given that that n>50, where n is the sample size, the size of the data set is satisfactory. 

The rows are as following:

State: The name of the State as a location.\
Date Local: The date when pollutants were measured.\
NO2 Mean:The  mean concentration of NO2 (Nitrogen Dioxide)\
NO2 AQI: The air quality index of NO2 \
O3 Mean:The calculated air quality index of O3 (Ozone)\
O3 1st Max Hour:The maximum value obtained for O3 concentration\
O3 AQI:The air quality index of O3\
SO2 Mean:The  mean concentration of SO2 (Sulphur Dioxide)\
SO2 AQI:The air quality index of SO2\
CO Mean:The  mean concentration of CO (Carbon Monoxide)\
CO AQI:The air quality index of CO


# III. Packages

The following packages need to be installed:pandas, seaborn, bokeh, and matplotlib.\
Important tools used for data visualization are pandas,numpy, seaborn,bokeh, and matplotlib.\
Pandas was used to clean the data (drop values).

# IV.Project Explanation
The following are lines and explanations for each input.

In[7] Import the packages listed above, remove warnings,import the csv file, and view the data. \
In[8] View the data's shape.\
In[9] Check what type of data is being used.\
In[10] Test for columns with missing values.\
In[11] Drop columns with missing values.\
In[12] View the number of monitoring sites by state.\
In[13] Drop all columns that aren't being analyzed.\
In[14] View data header.\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/table.png)\
In[15] View data shape, again.\
In[16] View data tail.\
In[17] Seaborn bar plot for NO2 Mean (by state)\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/barchart1.png)\
In[18] Seaborn bar plot for O3 Mean (by state)\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/barchart2.png)\
In[19] Seaborn bar plot for CO Mean (by state)\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/barchart3.png)\
In[20] Seaborn bar plot for SO2 Mean (by state)\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/barchart4.png)\
In[21] Plot all pollutants by state (bar plot).\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/bargraph.png)\
In[46] Scatter plot for SO2 Mean and NO2 Mean by State.\
![alt text](https://github.com/kstaud85/dvproject3/blob/master/scatter.png)\
In[43] Bokeh Plot for SO2 AQI by State.
![alt text](https://github.com/kstaud85/dvproject3/blob/master/bokeh_plot.png)\


# V.Conclusion

In conclusion, I found the O3 Mean to be the most evenly distributed pollutant.\
O3 (Ozone) are pollutants emmited by cars,chemical plants,etc.\
States with larger populations unsuprisingly had higher levels of pollutants.\
An improvement to this dataset could be adding pollutant types or pollutant causers such as the number of cars owned. 

# VI. Related Efforts

This kernal currently has many attempts to reproduce it on kaggle. 






