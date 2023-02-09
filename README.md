This is an example of a Kmeans algorithm used on a very small "dataset" (in fact i's just a table of points) for anyone who's trying to figure out how it works.

# KMEANS CLUSTERING
- It's a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). 
- Its goal is to find groups in the data, with the number of groups represented by the variable K. 
- It works iteratively to assign each data point to one of the K groups based on the features that are provided.


# HOW DOES IT WORK
Step-1: Select the number K to decide the number of clusters.

Step-2: Select random K points or centroids. (It can be other from the input dataset).

Step-3: Assign each data point to their closest centroid, which will form the predefined K clusters.

Step-4: Calculate the variance and place a new centroid of each cluster.

Step-5: Repeat the third steps, which means reassign each datapoint to the new closest centroid of each cluster.

Step-6: If any reassignment occurs, then go to step-4 else go to FINISH.

Step-7: The model is ready.

<img src="https://static.javatpoint.com/tutorial/machine-learning/images/k-means-clustering-algorithm-in-machine-learning.png"/>

# How to choose the value of "K number of clusters" ?
<b><i> The elbow method ! <b/><i/> 
  </br>
  </br>
<img width= '500px' src="https://media.licdn.com/dms/image/C4E12AQHnQ7zAvCnvZg/article-inline_image-shrink_1000_1488/0/1520190900650?e=1680739200&v=beta&t=ZPJXPcvm5as8bKz6E2wTL_ci2pmx8Lbd7eKaQpJDafM"/>

