# Data_Science_Projects
1. Market_Expansion_for_a_Sports_Equipment_Business
A retail company(hypothetical) selling sporting goods, equipment, sports apparel, and much more, for various sporting activities, all under one roof.
Business is booming and the company has decided to expand its operations. For the same, the company is looking to setup stores in Florida, starting with the city of Tampa, Florida. The task is to identify such neighborhoods and present an analysis, outlining which neighborhood(s) should the company setup their retail stores.
### Project Overview
We worked on clustering sports venues in Tampa using K-means clustering. The goal was to group similar venues based on their geographical locations (latitude and longitude).

## Steps Involved
API Data Parsing:

1. We started by extracting venue data from a provided JSON response, which included venue names, coordinates, and categories.
Data Preparation:

2. We prepared the data for clustering by extracting the latitude and longitude of each venue.
We converted a list of sports and recreation categories into a concise format to understand the types of venues we are working with.
Combining Neighborhood Data:

3. We integrated a list of neighborhoods in Tampa with existing borough data to expand our dataset.
K-means Clustering:

4. We performed K-means clustering on the venues based on their geographical coordinates.
The number of clusters (k) was set to 4.
We used the KMeans class from the sklearn.cluster module to fit the model and predict cluster labels for each venue.
Adding Cluster Labels:

5. We added the cluster labels to the original DataFrame, placing the new column at the end to avoid index errors.
