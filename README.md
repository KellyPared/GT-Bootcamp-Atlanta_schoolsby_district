# gt-TAAK-group-project1

[Project Proposal Document](https://docs.google.com/document/d/1LoP-4n8t47MM8Alf8_9MgfR9wXOitiEc4cgWyH3aJq8/edit?usp=sharing)

[Project Proposal Presentation](https://www.canva.com/design/DAFY_fhts1s/8oWl-UHsY0zsUQkcohVLrA/edit?utm_content=DAFY_fhts1s&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

### Database, Data Collection and Analysis
* [Edge Open Data](https://data-nces.opendata.arcgis.com/datasets/nces::school-district-composites-sy-2021-22-tl-22/explore?location=33.748310%2C-84.391110%2C11.66)

This project determines the average housing price per district and analyzes the schools and crime in the same area.

Zip Codes were pulled from an API and the crime data was cross-referenced against these zipcodes.
Data from the Great Schools API was pulled using the zipcodes and corssed referenced.

### School Data
The Great School API data needed a lot of processing the information on the rating of schools was not always available.  Manual input was used to enter in information from the [Niche website](https://www.niche.com/k12/search/best-schools/m/atlanta-metro-area/). Niche has a large collection of information. It charges money for all data per download and is not free for use.

During the school data clean up- many NaN and school outliers were filtered and the latitude and longitude was evaluated. 

GeoSpatial/Vector Data was used to map out the schools on the Atlanta zip code area. Vector Data is a representation of specific features on the Earth’s surface and it consists of lines, points and polygons. This data can be expanded and analyzed as a DataFrame.  DUring analysis the school data['zip', 'name', 'rating', 'lat', 'lon' and 'new rating'].


