# capstone-project
Identifying Accessibility Deserts in San Francisco

As someone with a disabled brother, I would like to use my time in the program to develop an interactive map that will identify accessibility deserts in San Francisco. To accomplish this, I will first use elevation contour maps to determine, with machine learning, a function that will predict elevation given a click on a map of the city. Then, factoring in the distance and change in elevation to get to the nearest bus stop, I will be able to use this information to create a heatmap of the city, with a focus on ease of accessibility. This analysis could also benefit private transportation companies like Lyft and Uber to help select the easiest locations for pickup and where to send drivers to serve the handicapped. This project could also be extremely useful for company marketing.


## SF Distance to Transit Stop
This graph, of the distance to the nearest transit stop from a location in the city, was made with data from over 9000 requests of the Google Places API.

![download 1](https://user-images.githubusercontent.com/29785389/43613806-c29a8456-9665-11e8-9e3a-d18786a7a041.png)


## Topology of SF
This Random Forest model of the topology of San Francisco was created with data from over 9000 requests of the Google Maps Elevation API.

![download 5](https://user-images.githubusercontent.com/29785389/43856146-8fa4018a-9afc-11e8-9902-0fef6a850484.png)


## Elevation Contour Lines
This image is of elevation contour lines in San Francisco, courtesy of DataSF and GeoJSON.
https://data.sfgov.org/Energy-and-Environment/Elevation-Contours/rnbg-2qxw#About (click ESRI)

![screen shot 2018-07-23 at 12 05 43 pm](https://user-images.githubusercontent.com/29785389/43097770-ee72bfa4-8e71-11e8-9deb-bf77d46fe40b.png)


## SFMTA Bus Stops
This image is of SFMTA bus stops courtesy of Data SF and GeoJSON.
https://transit.land/feed-registry/operators/o-9q8y-sfmta

![screen shot 2018-07-23 at 12 05 02 pm](https://user-images.githubusercontent.com/29785389/43097606-6c48fa3e-8e71-11e8-955d-d72b7bb5bf69.png)




