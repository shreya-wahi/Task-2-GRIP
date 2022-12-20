# Task-2-GRIP
Prediction using Unsupervised Machine Learning.
The aim of the task is to find the optimum number of clusters forming in the given data.
We proceed by importing various Library from plotting and reading excel files. Further we add Scikit Learning library for the import of KMeans by which we will find the number of clusters
We solve this task by The Elbow Method. We first find the inertia of KMeans, that is, we find the squared distance of every point.
we plot the graph of the sum of squares that comes out as the shape of an elbow. We see the point after which the sum of squares stop decreasing significantly.
For the data in question, the point is 3. And again we apply the fucntion of KMeans assuming number of clusters to be 3.
We plot our data with respect to first two columns, and we see 3 major clusters with their markd centrois. 
