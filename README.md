# Data_Science_Projects
1. Market_Expansion_for_a_Sports_Equipment_Business
   
A retail company(hypothetical) selling sporting goods, equipment, sports apparel, and much more, for various sporting activities, all under one roof.
Business is booming and the company has decided to expand its operations. For the same, the company is looking to setup stores in Florida, starting with the city of Tampa, Florida. The task is to identify such neighborhoods and present an analysis, outlining which neighborhood(s) should the company setup their retail stores.
### Project Overview
We worked on clustering sports venues in Tampa using K-means clustering. The goal was to group similar venues based on their geographical locations (latitude and longitude).

## Steps Involved


1. API Data Parsing: We started by extracting venue data from a provided JSON response, which included venue names, coordinates, and categories. We have used foursquare api to get nearby treading venues.


2. Data Preparation: We prepared the data for clustering by extracting the latitude and longitude of each venue.
We converted a list of sports and recreation categories into a concise format to understand the types of venues we are working with.


3. Combining Neighborhood Data: We integrated a list of neighborhoods in Tampa with existing borough data to expand our dataset.


4. K-means Clustering: We performed K-means clustering on the venues based on their geographical coordinates.
The number of clusters (k) was set to 4.
We used the KMeans class from the sklearn.cluster module to fit the model and predict cluster labels for each venue.

5. Adding Cluster Labels: We added the cluster labels to the original DataFrame, placing the new column at the end to avoid index errors.
## Conclusion
This project involved parsing venue data, preparing it for clustering, and using K-means to group venues based on location. The final output was a DataFrame with added cluster labels indicating the group each venue belongs to, which can be used for further analysis or visualization.








