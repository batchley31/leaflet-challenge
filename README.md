# leaflet-challenge

I created a variable for the URL of the JSON data from the USGS website so import all the data that had all the earthquakes for the past week. I then created my map with the center somewhere around middle of the US based on latitude and longitude corrdinates.  After that I added my title layer to the map to be able to overlay the visualizations of the earthquakes has they show up on the map from the data.

After that I pulled my JSON data through using d3 to fetch all the data from the JSON file. Using a function I created my mapstyle and changed all the different variables like opactiy, fillColor, the radius etc. I also created a function to change the color of the earthquake cirlce based on how deep it was in the earth.  And the last function I used for my earthquake visuals was for the radius or how big the circle would show depending on the magnitude of the earthquake.

At the end of my code I ceated a legend in the bottom right that shows the different color ranges for the depth of each earthquake.
