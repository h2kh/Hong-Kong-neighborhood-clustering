# Clustering Hong Kong's neighborhoods
### *Find your next apartment in similar yet cheaper locations*
---------

_Introduction_:

Hong Kong is home to people from more than a hundred countries. Because of Hong Kong's status as an international financial center with offices from many multinational corporations, it has a highly transient population of expat workers who are often blindsided by a city that defies most of its portrayals in media. One common issue is the relative absence of English as a medium of communication in comparison to an apparently similar city like Singapore. Not knowing Cantonese or Mandarin can cause quite a few difficulties in daily life; foremost among these is finding the right apartment in the right neighborhood.

Choosing a suitable neighborhood depends on varied factors including age and family status. In this project, we aim to characterize Hong Kong's neighborhoods based on the types of businesses and amenities that are situated in those neighborhoods. We will then use this data to perform K-means clustering on the neighborhoods and come up with two useful widgets that identify similar neighborhoods with cheaper rents than a given one. 

This analysis will be especially useful for foreign workers in Hong Kong who are trying to find a home in the city. It will also be useful for local Hong Kong residents who, despite their familiarity with the city, can still benefit from the data that we collect on more than 3000 venues and our objective analysis on said data.


_Data_:

We will use data from [Spacious](https://www.spacious.hk/en/hong-kong) which is a property leasing website. This dataset has the names and average rent per square foot for 128 neighborhoods in Hong Kong. We will supplement this data with the coordinates of each of these neighborhoods that we retrieved using the Python GeoPy module.

![alt text](https://github.com/h2kh/Coursera_Capstone/blob/master/Capture.JPG)

In addition to the dataset above, we will use the Foursquare API to collect information on the venues within each neighborhood. Once 
