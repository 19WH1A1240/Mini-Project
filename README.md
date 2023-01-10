# Mini-Project-UBER DATA ANALYSIS USING K-MEANS CLUSTERING ALGORITHM

## Problem Description: 
 In this project we have analyzed the Uber Pickups in New York City. The dataset is obtained from the kaggle from 2019-2020 Uber Pickups Data. We have applied K means clustering algorithm to understand the trips taken on uber in the New York City.

## Software and Libraries:
    1.pandas
    2.matplotlib
    3.folium 
    4.seaborn
    5.sklearn
    6.Python 3
    
## Dataset:
 There are total one crore plus observations and twelve columns.The dataset contains data from April to September 2019 and January to June 2020.The analysis is done on the complete dataset. Dataset : Uber Pickups in New York City.
 
## Images
![git1](https://user-images.githubusercontent.com/69394589/211569853-87ecac3f-590b-48ee-8786-b58116a1c32c.png)

The dataset is large so only few values are printed. Mainly there are 4 columns and are described as below:

 • Date/Time : The date and time of the Uber pickup
 • Lat : The latitude of the Uber pickup
 • Lon : The longitude of the Uber pickup
 • Base : The TLC base company code affiliated with the Uber pickup
 
 • In the above chart Elbow method is used to find the optimal value of k by fitting the model with a range of values for K.
 ![git2](https://user-images.githubusercontent.com/69394589/211570543-2a1912c4-4f2c-4769-94f7-fd34b632bd83.png)

• Analyzing the data by Weekday and Frequency
![map1](https://user-images.githubusercontent.com/69394589/211570779-073093b4-e358-4ff5-8d14-87acf3ee5b56.png)

![map](https://user-images.githubusercontent.com/69394589/211571847-b3bdf0d3-f82f-48b0-af04-c23cf2ab7f50.png)
•The above chart shows the all six centroids have been plotted on the map.Now these centroids can be really helpful by acting as a hub so whenever a uber recives a request for ride it can check the minimum distance to each of these centroids.

•Analyzing the Number of trips in each Cluster
![ud](https://user-images.githubusercontent.com/69394589/211571920-402503eb-6298-44aa-be98-f3737338961f.png)





