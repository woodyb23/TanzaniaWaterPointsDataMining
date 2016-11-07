# TanzaniaWaterPointsDataMining

## About me and Tanzania Water Data Mining Project
I went to school for Computer Science but dropped out so I could make money because I could not afford it at the time.
Been working with databases, mostly SQL Server for 12 years now. Have been getting into learning about data mining and
also cryptocurrency. This post will be my leanings from competing in a data mining competition to predict water points 
in Tanzania.

Here is the competition link : https://www.drivendata.org/competitions/7/page/25/

Just started out looking at the data and getting familiar with it. 
Use SSIS to match the data with the labels based by id.
Learning R in my part time as well because I noticed that SQL Server 2016 will now allow coding in R. 
Using tutorials from Code School to learn the basics.
I am just trying out new things here so please feel free to send comments or suggestions.
The steps I will be taking to analyze the data are:

* Define the problem
* Prepare data
* Explore data
* Build Models
* Explore and validate models

## Define The Problem
Predict the operating condition of a waterpoint for each record in the dataset. The data is given in two seperate csv files. One has the data points and the other has id and label of operational status. 

## Prepare data
Need to merge the csv files based upon the id so that I can have all data points with its corresponding operational label. Will do this through a Sql Server Integeration Services package.


### Resources

[MSDN - Data Mining Concepts] (https://msdn.microsoft.com/en-us/library/ms174949.aspx)
