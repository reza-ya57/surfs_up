# Surfs_up Analysis projects
## Overview of the Analysis

-	In this study we provide some valuable information for decision making process of choosing a best location for running a surf shop. We analyze the temperature for two major time of the year (June and December) and provide statistical info to give a clear vision of the weather.
Results:
Based on this study you can see below conclusion:
-	Minimum temperature for surfing usually is over 60s and we can see in December which is one of the coldest months of the year 75% of the days have a temperature over 69 degrees. 
-	Maximum temperature also is about 80s and over this is not very comfortable time for surfing. By looking at June temperature which should be hottest month of the year we can see 25% of the June would be higher than 77 degrees which still is a good weather for surfing.
-	By looking at statistical result we can say variation of the temperature also is about 3 to 4 degrees during the hottest and coldest month of the year in Oahu.
-	Average temperature for June and December also shows majority of the days in Oahu would be a good time for surfing. 
Summary:
In summary, Oahu could be a good place to running a surf shop and also sell Ice Cream!
There is a good chance to have lot of days with ideal temperature for surfing and enjoying the vacation in Oahu.
Also I can offer two more study as below to make sure our conclusion is more reliable:
1-	Check the precipitation for June
---
dec_prcp = []
dec_prcp = session.query(Measurement.prcp).\
    filter(extract('month',Measurement.date) == 6).all()
---
2-	Check the precipitation for December
---
dec_prcp = []
dec_prcp = session.query(Measurement.prcp).\
    filter(extract('month',Measurement.date) == 12).all()
---
