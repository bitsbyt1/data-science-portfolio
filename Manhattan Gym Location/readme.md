# Analyzing a location to open a new fitness center in Manhattan, New York #

## The Problem ##

Analyzing the number of fitness centers in Manhattan, New York to decide where would be a good location to start a new gym.
Who would be interested in this project: Investors and business owners who would like to start a gym, as well as fitness enthusiasts who would like to live closer to a gym or fitness center.
  
## The Data ##
  
I used the 'newyork_data.json' dataset from IBM, as well as the Foursqaure API to get
the information on gyms and fitness centers in Manhattan
  
## Methodology ##

I started off by loading the newyork_data.json Json file into a data set. I organized the
data set into four columns - Borough, Neighborhood, Latitude and Longitude.
I then took the data from the new york dataset and created a new dataset for just
Manhattan, which consisted of clusters of all the Neighborhoods in Manhattan using
their Latitude and Longitude coordinates
After that I used the Foursquare API combined with the Manhattan Neighborhood
Dataset to get a list of every Gym and Fitness center in the Borough along with their
Latitude and Longitudes.
Then using Folium I generated a heatmap to see the density or 'heat' of the number of
Gyms and Fitness Centers in different parts of Manhattan


## Analysis ##

As you can see, Manhattan is denser (has more neighborhoods) toward the water and
the South West end of the borough, and less dense in the North East end.
  
