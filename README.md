# Geo-tagged Tweet Collection and Visualization

![tweets_map](https://user-images.githubusercontent.com/77243665/106077973-6db0e500-60c7-11eb-95b8-3dc5a3614951.png)

The map uses QGIS to visualize the geographic location (longitude and latitude) of the information sent by Twitter users in the United States at 23:44 PM Seattle time on January 27th.
The data is captured by running a python script. To retrieve geotagged tweets, three bounding boxes are defined, namely "Washington State, New York, and California". The filter parameter is "Geography, GIS, Data Science" and the time limit is set to 60.
These data are mainly concentrated on the East coast and West coast. Mainly distributed in New York and California. Florida's data also looks dense.
The data distribution probablely affected by the population size of each state. It affected by time-zone as well. There is three-time-zone between East Coast and West Coast. At this time, it was around 8-9pm on the East coast, and the West coast was about to enter the midnight. This point affects the capture of data distribution on the East coast and West coast. Moreover, due to the time-zone, the data gradually decreases from East to West. Anyway, GIS and Data science seem to be a hot topic.
