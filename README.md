# surfs_up

## Overview
The purpose of this project was to analyze weather data to determine the possibility of opening a successful surf and ice cream shop in Oahu, Hawaii. In this part of the project, we wrote queries to analyze weather in June and December to see how consistent the weather was throughout the year and if this shop could be sustainable year-round.

Applications: SQLite, SQLalchemy, Flask, Jupyter notebook, Python

## Results
Below are three key differences I found when analyzing weather in June and December. 
- Temperatures in June are higher than December. The average temperature in June is about 75 degrees and is 71 degrees in December.
- The range of temperatures is greater in December than in July. December ranges from 56 degrees to 83 degrees (a range of 27) while June ranges from 64 degrees to 85 degrees (a range of 21).
- Although the temperature ranges weren't off by a lot, I noticed that 75% of the days in June had temperatures of 73 degrees or high while December only had 25% of days with a temperature of 74 degrees or higher.

<p float="left">
  <img width="136" alt="June Temps" src="https://user-images.githubusercontent.com/90946252/142322107-311887a5-8308-438c-9b5e-914ae818d168.png">
  
  
  <img width="157" alt="December Temps" src="https://user-images.githubusercontent.com/90946252/142322260-fa479f0f-9012-4449-8a64-15d9c047e7f1.png"> 
</p>

## Summary
Overall, both months have good temperatures. Although June is definitely warmer, the temperatures do not vary that much. The 25%, 50%, and 75% ranges are all only 2-3 degrees lower in December. Additionally, neither month strays very far from the average. June has a standard deviation of 3.25 while December has a standard deviation of 3.75.

Here are two additional queries I would run to analyze the weather in these months:
1. I think it would be very important to analyze the precipitation for June and December. Does one month get a lot more rain than the other? If so, by how much?
2. I would also run a query to analyze which stations are being used in these months. I would hope to see that the stations are being used similarly for each month so that we are getting consistent data.
