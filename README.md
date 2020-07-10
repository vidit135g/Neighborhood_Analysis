# Neighborhood_Analysis
Data Science project for detailed analysis of neighborhood areas.

<div class="christmas_promotion_boxes">
    <img src="https://raw.githubusercontent.com/vidit135g/Neighborhood_Analysis/master/Area%20analysis/visuals/1.PNG" width="500" height="220"/>
    <img src="https://raw.githubusercontent.com/vidit135g/Neighborhood_Analysis/master/Area%20analysis/visuals/2.PNG" width="500" height="250"/>
    <img src="https://raw.githubusercontent.com/vidit135g/Neighborhood_Analysis/master/Area%20analysis/visuals/3.PNG" width="500" height="220"/>
    <img src="https://raw.githubusercontent.com/vidit135g/Neighborhood_Analysis/master/Area%20analysis/visuals/4.PNG" width="500" height="250"/>
    <img src="https://raw.githubusercontent.com/vidit135g/Neighborhood_Analysis/master/Area%20analysis/visuals/5.PNG" width="530" height="270"/>
</div>

### 1. Introduction:
The primary goal of this project is to help people in exploring their neighborhoods in order to find the best things out there.For this report, we will focus on Scarborough, Toranto neighborhood only.

There are so many migrants in different states of Canada who had to settle themselves for which they had to do a lot of research. The research here comprises of good prices for housing, good schools, best places to buy grocery etc. This project is for those people who are looking for the best places and the best availabilities within an area. Other applications may include shopping malls, super stores, schools, cafe, medical shops, hospital etc. This project helps in creating an enhanced analysis and study of features for the migrants of Scarbough in order to search for the best neighborhood.

The features include the median house price and better schools on the basis of the number of ratings and scores. We will also try to focus on the crime rates of the particular area, roads, weather and availability of resources. It will help people be aware of their area and the neighborhood before actually moving to that city.

### 2. Data Section
Data Link: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Will use Scarborough dataset which we scrapped. Dataset consisting of latitude and longitude, zip codes.

### Foursquare API Data:

We have used the Foreqsuare API ( Free Version ) because of the fcat that it has a large database comprising of a lot of info about dfferent places and different areas.Especially their places API which provides the ability to perform location search, location sharing and details about a business.

After finding the list of neighborhoods, we then connect to the Foursquare API to gather information about venues inside each and every neighborhood. For each neighborhood, we have chosen the radius to be 100 meter.

The data retrieved from Foursquare contained information of venues within a specified distance of the longitude and latitude of the postcodes. The information obtained per venue as follows:

Neighborhood
Neighborhood Latitude
Neighborhood Longitude
Venue
Name of the venue e.g. the name of a store or restaurant
Venue Latitude
Venue Longitude
Venue Category
