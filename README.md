# surfs_up

## Overview
This report will help W. Avy to make decision if it is feasible to open the surf and ice cream shop for year round in Oahu.
So following analysis will be performed:
1. Analysis of temprature for the month of June
2. Analysis of temprature for the month of December

## Results

The data from sqlite file is processed in [surf_up](https://github.com/ajinderbains/surfs_up/blob/master/SurfsUp_Challenge.ipynb) for the months of June and December and following observations are made .

- The average temprature for the month of June is 75&deg;F and for the month of December it is 71&deg;F.
- The maximum temprature in the month of June is 85&deg;F and for the month of December it is 83&deg;F .
- The minimum temprature in the month of June is 64&deg;F and for the month of December it is 56&deg;F .

#### Temrature statistics for the month of June
![chart1](https://github.com/ajinderbains/surfs_up/blob/master/Resources/challenge_june_temp.png)

#### Temrature statistics for the month of December
![chart2](https://github.com/ajinderbains/surfs_up/blob/master/Resources/challenge_dec_temp.png)

## Summary
- From December and June's temprature it is analysed that temprature is in favor of opening surf and icecreame shop for year round.Though minimum temrature is recorded 56&deg;F in the month of December that too fall in lower percentile (25%).

But only temprature data is not sufficient  to make decision so I have also used the following 2 queries to analyze data.
- [Precipation_query](https://github.com/ajinderbains/surfs_up/blob/master/additional_query1.ipynb) is used to find the statistics for the month of June and December for precipitaion.precipitation is higher in the month of December as compare to month of June.
#### Precipitation statistics for the month of June
![chart3](https://github.com/ajinderbains/surfs_up/blob/master/Resources/challenge_june_prcp.png)
#### Precipitation statistics for the month of December
![chart4](https://github.com/ajinderbains/surfs_up/blob/master/Resources/challenge_dec_prcp.png)
- [Station_query](https://github.com/ajinderbains/surfs_up/blob/master/additional_query2.ipynb) is used to find the statistics for the month of June and December for precipitaion and temprature based on station "USC00519281" (having the most count).Precipitation is higher in the month of December as compare to month of June.Temprature is higher in the monthe of June as compare to December for station USC00519281
#### Precipitation and Temprature statistics for the month of June for station USC00519281
![chart5](https://github.com/ajinderbains/surfs_up/blob/master/Resources/challenge_june_stat.png)
#### Precipitation and Temprature statistics for the month of December for station USC00519281
![chart6](https://github.com/ajinderbains/surfs_up/blob/master/Resources/challenge_dec_stat.png)
