# gt-TAAK-group-project1


[Project Proposal Document](https://docs.google.com/document/d/1LoP-4n8t47MM8Alf8_9MgfR9wXOitiEc4cgWyH3aJq8/edit?usp=sharing)

# Presentation
[Project Proposal Presentation](https://www.canva.com/design/DAFY_fhts1s/8oWl-UHsY0zsUQkcohVLrA/edit?utm_content=DAFY_fhts1s&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

# The Process
### Database, Data Collection and Analysis
* [Edge Open Data](https://data-nces.opendata.arcgis.com/datasets/nces::school-district-composites-sy-2021-22-tl-22/explore?location=33.748310%2C-84.391110%2C11.66)

This project determines the average housing price per district and analyzes the schools and crime in the same area.

[Zip Codes](https://app.zipcodebase.com/api/v1/radius) were pulled from an API and the crime data was cross-referenced against these zipcodes.
Data from the Great Schools API was pulled using the zipcodes and corssed referenced.

### School Data
The Great School API data needed a lot of processing the information on the rating of schools was not always available.  Manual input was used to enter in information from the [Niche website](https://www.niche.com/k12/search/best-schools/m/atlanta-metro-area/). Niche has a large collection of information. It charges money for all data per download and is not free for use.

During the school data clean up- many NaN and school outliers were filtered and the latitude and longitude was evaluated. 
Once the DataFrames were analyzed, parsed and cleaned, different plots were used to determine the best way to show the data.


GeoSpatial/Vector Data was used to map out the schools on the Atlanta zip code area. Vector Data is a representation of specific features on the Earth’s surface and it consists of lines, points and polygons. This data can be expanded and analyzed as a DataFrame.  There are many packages and geoSpatial data that can be used. Google, Folium and GeoPandas were investigated. During analysis the school data['zip', 'name', 'rating', 'lat', 'lon' and 'new rating'].


### Crime Data


### Housing Data


# The Analysis and Conclusion
What is the distribution of Atlanta High Schools?
* As far as the physical distribution of the high schools, there is a large grouping on the East side of the city of Atlanta along longitude -84.35.
* The three zip codes with the most schools are 30306, 30314, and 30315.

What is the breakdown of Atlanta High Schools?
* Of the high schools in the Atlanta area there is a wide variety of different average scores that are passing.
* Surprisingly, there is a large number of schools that are passing with A’s as an average.
* It was assumed that the average letter grade would be closer to B’s
* It should be understood that the high schools in the data set is made up of public, private, and charter instead of only one type.

What is the correlation between high school ratings and neighborhood crime?
* In areas where there are higher rates of crime, there are fewer high schools located.
* It would be premature to assume that the lack of high schools has any correlation towards crime since there are other factors such as population density.


What is the distribution of crime in Atlanta?
* Most of the crime is centered in the Northeast with a large concentration in the zip code 30318.
* If we are referring to crime relative to population size the zip codes of 30308, 30326, 30303, and 30324 have higher rates of crime then most of Atlanta.


What is the correlation between crime rates and housing prices?
* Crime does seem to play a factor, and this is on clear display with the comparison between zip code: 30318 being the highest crime rate and zip code: 30327.
* Most of the zip code with a decent amount of crime (+1000 in 2022) seen with similar levels of average housing cost.
* The exception is in the north around latitude: 33.80, longitude: -84.35
* These exceptions raise the question of how much of a pull these other factors in the Northern part of Atlanta have that they are starting to outweigh factors like crime.


What is the distribution of average housing prices in Atlanta?
* The average housing price seems to be centralized in the Northern part of Atlanta.
* This was interesting since it was first assumed that a large part of the average house price distribution relative to Atlanta would contain higher prices in the center of the city since land would be more at a premium.


Is there a trend regarding price and geographic location relative to Atlanta?
* Most of the less wealthy areas of the city are in the Southwestern part of the city.



