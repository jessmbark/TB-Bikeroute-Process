# TB-Bikeroute-Process
The data, notebooks, and process notes for TN-Bikeroute-Project
---
## Content Description
I called this project "Bike Route Report Card." This was initially the concept I sought to do with Project 2, but I could not get it to work in time.

I found that Tennessee had over 12,500 miles of roads graded along the nationally-recognized scale. Of that mileage, more than 2,500 miles received the worst possible grade for cyclists. Only 2,000 miles received an A grade. Half of the mileage was D or below. 

## Finding and analyzing the data

First, I found this data by seeing what maps the state had for its cyclists. I found [this KMZ file.](https://www.tn.gov/content/dam/tn/tdot/multimodaltransportation/bicycle-maps/bicycle-level-of-service/BLOS_BlueARedF.kmz) I had the most difficult time getting this file to open in QGIS. It seemed to open in Google Earth, but it ultimately took help from ChatGPT to get the file to open. I uploaded the notebook with the code to get functionality into this repository.

Once in QGIS, getting the correct visualization was not that difficult. I selected a categorized color scale, with A being green and F being red, color-coding all the routes based on grade. However, I realized that ChatGPT's code meant that everything that had uploaded into QGIS was a string and not a real number. Try as I might, I ultimately had to copy and paste the attribute table into a separate Excel file because I could not get QGIS transformations to either work at all or work without rounding the numbers. 

There were a lot of data points in the attribute table that might have been interesting to pull from, but without being able to talk to someone at the state Department of Transportation quickly, I did not want to make any assumptions about the data's columns.

## Wins & Losses

I am glad that this project was able to come into fruition, but I wish the Mapbox scrollama template allowed for the user to engage with the map more directly. The file has some information, like route name, that I think would have been fun to add.

I also wish that I had more time to incorporate county data into this project. Project 2 focused on bicycle crash data collected across Tennessee's counties, and I think an analaysis comparing counties with high crash numbers and high unsafe route mileage would be worthwhile. I honestly think that after the program ends, I may pursue a project to this end.
