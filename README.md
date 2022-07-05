
# Weather Station Clustering using DBSCAN & scikit-learn 

DBSCAN used for to find the group of stations which show the same weather condition. As you can see, it not only finds different arbitrary shaped clusters, can find the denser part of data-centered samples by ignoring less-dense areas or noises.


## Features

- Radius of Neighbourhood(R)
   
     R that if includes enough number of points within, we call it dense area.

- Minimum number of neighbours(M)
      
     The minimum number of data points we want in a Neighbourhood to define a cluster.

![points](https://miro.medium.com/max/778/1*NSTKALeiFbGg4J0UQSI0tg.png)

#### Core point  - which have M number of points in R radius.
#### Border point - which have less than M points in R radius.
#### Outlier - no points in R radius.


## Documentation

Data is from the IBM object storage.
[Dataset](https://github.com/hellfire95/DBSCAN-Visualization-data-of-Weather-Stations-of-Canada/blob/main/About%20the%20Datta%20set%20of%20%20Weather%20Station%20of%20Canada.ipynb)

![data](https://github.com/hellfire95/DBSCAN-Visualization-data-of-Weather-Stations-of-Canada/blob/main/Data.png?raw=true)

## Weather  Stations


![Weather stations](https://github.com/hellfire95/DBSCAN-Visualization-data-of-Weather-Stations-of-Canada/blob/main/Locations%20on%20map.png?raw=true)

## Clustering Based on Locations

![locations clustering](https://github.com/hellfire95/DBSCAN-Visualization-data-of-Weather-Stations-of-Canada/blob/main/clustering%20based%20on%20location.png?raw=true)

## Clustering Based on Temperature & locations

![temp clust](https://github.com/hellfire95/DBSCAN-Visualization-data-of-Weather-Stations-of-Canada/blob/main/clustering%20based%20on%20temp.png?raw=true)