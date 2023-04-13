# Finding Similar Neighbourhoods for a Thriving Restaurant (forked from former account)
-	Worked on a hypothetical business problem where a restaurant in Lagos, Nigeria was seeking to open a new branch in a different location with a similar neighborhood
-	Scraped the list of neighborhoods in Lagos from Wikipedia using Beautiful Soup and parsed the data into a data frame with pandas
-	Used Google's geocoding API to obtain the geographic coordinates of each neighborhood, and then applied Foursquare API to extract venue categories within a 1500-meter radius of those coordinates
-	Applied K-Means algorithm to cluster the neighborhoods based on the similarity of the top ten venue categories closest to them


