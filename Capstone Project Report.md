# Introduction/Business Problem 

In the city of Toronto, we are looking to open a new restaurant so the problem is where to open this restaurant. It should be beside an interesting place with a lot of visitors. I would think of opening the restaurant beside a university, a gym or an airport. Also, it should not be a quiet place like a residential place for example to not making noise to the neighbors.
I will try to explore Toronto venues using Foursquare and try to get the coordinates of the most important venues that I would like to open the restaurant around. 

# Data

There is a Wikipedia page with Toronto neighborhood data. Thiswikipedia page provides a list of postal codes in Canada staring with the letter “M” which means they are located within the city of Toronto in the province of Ontario.
We will scrape this page and wrangle the data we need, clean it and load it to a pandas dataframe to have a structured format.
Then, we will use a readily-available csv file with all the geographical coordinates of Canada postal codes to assign each neighborhoud the longitude and latitude using the Geocoder package.
We will filter to get the data for Toronto Neighborhouds only.
Then, we will use Foursquare to explore the venues using the neighborhouds coordinates and find the venues in interest for this project like universities, gyms or airports. This exploration will guide us with the best place to open a restaurant.
