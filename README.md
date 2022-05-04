# UNSUPERVISED MACHINE LEARNING ANALYSIS

## **Purpose of the Project**

In this project, data on Cryptocurrencies is been transformed and analyzed using unsupervised machine learning types,  transformation and clustering algorithms to group and create a classification system for active trading cryptocurrencies. 

# **Results**

The data was examined, cleaned and relevant data was extracted from the dataset. The principal component analysis technique was introduced to reduce the features since the there are so many in the the dataset. The technique was used to reduce the features to 3 thus preserving the original information while speeding up the machine learning model. 

![3 Dimensional Plot for PCA](/images/newplot.png)

Additionally, an elbow curve was created to determine the best value for K (K=4). The K-means algorithm is then used to group the data into 4 clusters. 

![Elbow Curve](/images/elbow_curve.png)

The project also uses hvPlot visualization library to visualize the results of the clustering. In the end a scatter plot is created to provide visualization on the total coin supply against the total coin mined of each class (cluster). 

![Scatter Plot of 4 clusters](/images/scatter_plot.png)
