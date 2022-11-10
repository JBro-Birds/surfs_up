# surfs_up

## Overview of Project
With my savings I'm willing to invest in a Surf and Shake shop serving surfboards and ice cream to locals and tourists, but I'll need investor backing during the startup phase.  I've put together a strong business plan and reached out to W. Avy, an investor who is famous for his love of suring.  The initial meeting with W. Avy went well but he has a concern about how the weather would impact the business.  W. Avy was burned in the past with what ended up as a failed surf shop which he believes was due to bad weather, and because of this he's concerned about the amount of precipitation on Oahu.  W. Avy knows I'm learning how to properly analyze data and asks if I can run some analytics on a weather data set he has from the very island where I'd like to open my shop, the beautiful Awahoo.

W. Avy has supplied me with the data he wants us to use and has asked me to look at a full year of data.  W. Avy doesn't just want to see a list of data, rather he wants to understand trends in the data.  For this analysis I'll use my Jupyter notebook, SQLite database, Python and Pandas skills to plot precipitation scores for a specific period of time in chronological order and show him how much it rained and if it was raining on the previous or subsequent days as well.  There's a slight possibility that W. Avy will ask me to duplicate this process in the future (to open other shops, or if Oahu doesn't turn out to be a good fit) so I'll take measures to ensure that I can efficiently and effectively produce the data trends and analysis in the future.

### Purpose
The purpose of this project is to produce additional temperature trends for W. Avy.  W. Avy liked my initial analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu in order to determine if the surf and ice cream shop business is sustainable year-round.  In order to show W. Avy the requested analysis I will query to retrieve all temperatures for June and December and run summary statistics for both months. 

## Results

June tempature subset listing is as follows:

![June_Temps](https://raw.githubusercontent.com/JBro-Birds/surfs_up/master/Support/June_Temps.png)

June tempature statistics are as follows:

![June_Temp_Description](https://raw.githubusercontent.com/JBro-Birds/surfs_up/master/Support/June_Temp_Description.png)

December tempature subset listing is as follows: 

![December_Temps](https://raw.githubusercontent.com/JBro-Birds/surfs_up/master/Support/December_Temps.png)

December tempature statistics are as follows:

![December_Temp_Description](https://raw.githubusercontent.com/JBro-Birds/surfs_up/master/Support/December_Temp_Description.png)

* The original six HR .csv files provided the foundation to build SQL tables and merge data together in order to produce the necessary data needed for the project.  Using the Quick DBD website the database ERD was constructed as follows:

## Summary

precipitation

by-station statistics to determine if more favorabe location of island for surfing



