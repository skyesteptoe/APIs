## World Weather Analysis

### Overview
For this exercise, we're expanding the PlayMyTrip app to include several new eleements. The first is to allow the user to specify their ideal min and max temperatures for their travel destinations. Incorporating this information, we can then identify potential travel destinations and nearby hotels. Finally, users will have the option to create a travel itinerary incorporating this information to select four cities to travel between complete with identified hotels.

### Weather Database

The first step of the analysis is to leverage the Open Weather Maps API to grab weather information from around the world. Several categories of information were selected in addition to city name and country:
1. Maximum Temperature
2. Cloudiness
3. Wind Speed
4. Humidity
5. Current Weather description

### Vacation Search 
The second step combined information obtained from Weather Maps with Google Maps to allow us to visually plot travel destinations with a hotel nearby. The goal of this exercise is to generate an image displaying locations of cities identified in the previous exercise wiht a daily maximum temperature falling between 75 and 90 degrees fahrenheit. (I was unable to generate figures with marker_layers.) 

### Vacation Itinerary
The final exercise combined information from the vacation search with Google Maps directions API. The user identifies four cities to create a 4-stop itinerary. I selected several cities from across the US, that I am quite certain are very far apart. Without the visual map, it's hard to make an informed choice! Next stop, Boot Camp tutor!

I selected a travel itinerary starting and ending in Bemidji, Minnesota followed by a stop in Andrews, Texas and onward to Creston (CO, IA, WA, or CA???) with another stop in Espanola (FL or NM!) and finally back to Bemidji. What a long, strange trip!


