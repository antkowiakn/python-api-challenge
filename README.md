# Python API Challenge  
## Part I 
  
Took 500+ random cities and collected current to time weather information.  
From all of the weather data created the following relationships:  
* Temperature (F) vs. Latitude  
* Humidity (%) vs. Latitude  
* Cloudiness (%) vs. Latitude  
* Wind Speed (mph) vs. Latitude  
  
Then ran linear regressions on each relationship based on the hempispheres as follows:  
* Northern Hemisphere - Temperature (F) vs. Latitude  
* Southern Hemisphere - Temperature (F) vs. Latitude  
* Northern Hemisphere - Humidity (%) vs. Latitude  
* Southern Hemisphere - Humidity (%) vs. Latitude  
* Northern Hemisphere - Cloudiness (%) vs. Latitude  
* Southern Hemisphere - Cloudiness (%) vs. Latitude  
* Northern Hemisphere - Wind Speed (mph) vs. Latitude  
* Southern Hemisphere - Wind Speed (mph) vs. Latitude  
   
## Part II  
  
Created a heat map that displays the humidity from each location from part one.  
Narrowed down the data frame to find ideal weather condtions that meet all below requirements:  
* Temperature between 75 and 85 degreees  
* Wind Speed less than 10 mph  
* Zero Clouds  
  
Using googles API find hotels within 5000 meters of the locations that meet the ideal weather requirements.  
Plot all of the hotels on the heat map and have clickable pins that hold the following:  
* Hotel Name  
* City  
* Country  
  
  
