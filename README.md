# Test_DS
# Static geographical information of CityBike‘s stations in Brisbane
This is an clustering analytics application based on the location of the bike stations. This application is build in with Python 3.

# Description:
- Input Data: Static geographical information of CityBike‘s stations in Brisbane ("Brisbane_CityBike.json")

- Languages: Python3

- Output: A csv file which contains original data and its label of cluster ("Groupes.csv")

# Clustering.py

- Reading the dataset in json format and converting it to a dataframe
- Preparing Input Data K-means algorithm works only on numerical features and so it needs to quantify the features in order to calculate distance between data objects. Here, we are implementing the KMeans on the locations (latitude and longitude).
- Determination the optimal nubmer of k using the elbow method.
 we have to select the value of k at the “elbow” ie the point after which the distortion/inertia start decreasing in a linear fashion.
- Application of the algorithm of k means.

- Exporting the result in csv format
