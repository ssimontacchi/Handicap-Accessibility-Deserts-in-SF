# capstone-project
Identifying Accessibility Deserts in San Francisco

As someone with a disabled brother, I would like to use my time in the program to develop an interactive map that will identify accessibility deserts in San Francisco. This project is important to me because my own brother is disabled and it is important to remember what able-bodied citizens take for granted on a daily basis. This project will also identify areas where we can improve transit options for the disable and bring shed light on market opportunities for private transportation companies. 

So far I have pulled the information for the heat-map from Google's Places and Elevation APIs, used Random Forest and kNN algorithms to accurately model them, and would next like to survey the handicapped community to better understand how these features should be weighted in the heat-map. 

Next, I would like to use the PUMS dataset, released by the US Census, to identify the neighborhoods where the physically disabled live in San Francisco, to identify if these communities intentionally have moved nearer to transit stops and how they have changed over time, and to show the impact of these accessibility deserts on the actual people of San Francisco. Due to the size of these datasets, I will use Spark to analyze them, which I have worked with extensively over the last four months as a full-time Fellow in Galvanize's Data Science Immersive program.


## Topology of SF
This model of the topology of San Francisco was created with data from nearly 10,000 requests of the Google Maps Elevation API.

![download 5](https://user-images.githubusercontent.com/29785389/43856146-8fa4018a-9afc-11e8-9902-0fef6a850484.png)


## SF Distance to Transit Stop
This graph, of the distance to the nearest transit stop from a location in the city, was made with data with a similar number of requests from the Google Places API.

![download 1](https://user-images.githubusercontent.com/29785389/43613806-c29a8456-9665-11e8-9e3a-d18786a7a041.png)


## Elevation Contour Lines
This image is of elevation contour lines in San Francisco, courtesy of DataSF and GeoJSON.
https://data.sfgov.org/Energy-and-Environment/Elevation-Contours/rnbg-2qxw#About (click ESRI)

![screen shot 2018-07-23 at 12 05 43 pm](https://user-images.githubusercontent.com/29785389/43097770-ee72bfa4-8e71-11e8-9deb-bf77d46fe40b.png)


## SFMTA Bus Stops
This image is of SFMTA bus stops courtesy of Data SF and GeoJSON.
https://transit.land/feed-registry/operators/o-9q8y-sfmta

![screen shot 2018-07-23 at 12 05 02 pm](https://user-images.githubusercontent.com/29785389/43097606-6c48fa3e-8e71-11e8-955d-d72b7bb5bf69.png)




