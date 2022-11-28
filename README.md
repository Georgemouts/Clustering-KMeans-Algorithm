# Clustering-KMeans Algorithm Implementation :page_facing_up:
A k means algorithm implementation in Java .Clustering points.
UOI-Project for computational intelligence course.

# Create dataset :file_folder:

we generate random points (x1,x2)[1200 points] in the plane as follows: 
1) 150 points in the square [0.75,1.25]x[0.75,1.25], 
2) 150 points in the square[0, 0.5]x[0,0.5],
3) 150 points in the square [0,0.5] x [1.5,2], 
4) 150 points in the square[1.5,2]x[0,0.5], 
5) 150 points in the square [1.5,2] x [1.5,2], 
6) 75 points in the square[0.6,0.8]x[0,0.4], 
7) 75 points in the square [0.6,0.8] x [1.6,2],
8) 75 points in the square[1.2,1.4]x[0,0.4],
9) 75 points in square [1.2,1.4] x [1.6,2], 
10) 150 points in square [0,2]x[0,2].



# Create K-Means algorithm 
We run the clustering program on the data set for M=3,5,7,9,11,13 groups. For each value of M do the following:
1) Perform 20 runs of the program with different (randomly selected initial centers) and
we keep the solution with the smallest clustering error.
2) Then display 2 plots 
  - one all with the points.
  - one with the positions of the centers found by the algorithm.
  
For each instance xi we calculate the **Euclidean distance ||xi-μk||2** from
the **center μk of the group** it belongs to and we sum the distances for all examples
xi.

# Results :memo:
Here is an image of all points from Dataset.

![alt text](https://github.com/Georgemouts/Clustering-KMeans-Algorithm/blob/main/images/all_points.png)

 The points (centers) which algorithm found for clustering for M=7.
 
 ![alt text](https://github.com/Georgemouts/Clustering-KMeans-Algorithm/blob/main/images/centroid_m%3D7.png)
