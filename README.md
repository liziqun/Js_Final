# Spatial Distribution of Urban Facility in Shanghai
### Ziqun Li
#### Final project for MUSA-611 JavaScript  
  
To the website, please click:https://liziqun.github.io/Js_Final/map.html  

##### What is this application for?
This project seeks to evaluate the urban space value for both the urban planner and property developer, and provide a basis for facility site selection. By using this app, it is possible for the users to find the specific area where certain type of facility are concentrated, and reasonably judge the value of real estate investment.

##### How to use this app?
The users could get a sense spatial distribution of different types of facility by dragging the slider. Besides, the users could easily find the total number of different types of facility in the whole city, as well as the relationship between the count of different types of facility in each grid cell through the charts at the bottom.

##### Data collection and transformation
Firstly, we download the Shanghai boundary data and POI data from both baidu api and mapbox api. Based on the collected data, we divide the whole city into 1500m*1500m fishnet in ArcGIS, and count the number of different types of facilities in each grid. After that, we transform the data into both .geojson and .json format that could be used in JavaScript.

##### Technologies 
mapbox, jquery, bootstrap, e-charts. etc  

![image](https://raw.githubusercontent.com/liziqun/Js_Final/master/img/app.png)


