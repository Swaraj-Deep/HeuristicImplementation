# HeuristicImplementation
Heuristic for Movement of the DTN Nodes
Give the number of DropBox
Give the number of Nodes
Location of the Nodes ,Pathway Matrix,Number of clusters,Initial Centers,Tower Range,And Number of Mules
The code will do the rest of the thing


Here is the Sample to run this


Enter the Number of DropBox:
10
Enter the Number of Nodes:
10
Enter the Location Of Nodes:
530793.55 2605536.70
528582.19 2605971.72
528145.07 2603757.81
529050.02 2603489.22
530391.39 2603112.21
531156.70 2604753.20
529878.03 2604032.26
529726.07 2604476.00
529223.00 2605040.15
529819.27 2605319.02
Enter the PathWay Matrix:
0 2.5 4.5 3.3 3.1 1.1 2.0 2.1 1.9 1.1
2.5 0 3.0 3.6 4.0 3.4 2.6 2.0 1.2 1.8
4.5 3.0 0 1.2 2.8 4.5 2.5 3.1 3.4 4.1
3.3 3.6 1.2 0 1.6 3.3 1.3 1.9 2.7 2.9
3.1 4.0 2.8 1.6 0 2.1 1.6 2.1 3.0 3.2
1.1 3.4 4.5 3.3 2.1 0 2.1 2.3 2.3 1.9
2.0 2.6 2.5 1.3 1.6 2.1 0 0.6 1.6 1.6
2.1 2.0 3.1 1.9 2.1 2.3 0.6 0 1.0 1.0
1.9 1.2 3.4 2.7 3.0 2.3 1.6 1.0 0 0.9
1.1 1.8 4.1 2.9 3.2 1.9 1.6 1.0 0.9 0
Enter the Number of Clusters:
3
Enter the Initial Clusters:
2 6 7
Initial Clustering 
******************* 
2-> [2,9]

6-> [1,6]

7-> [3,4,5,7,8,10]

Cost of the clusters : 9.899999999999999


After applying K Medoid Algorithm clusters are
********************************************** 
9-> [2,8,9,10]

6-> [1,6]

4-> [3,4,5,7]

After applying K Medoid Algorithm cost of the clusters : 8.299999999999999
Enter the Tower Range: 
2.5
Tower 1 is at 4
Tower 3 is at 8
Clusters after the tower installed at the group centers
******************************************************* 
4-> [3,4,5,7]

8-> [1,2,6,8,9,10]


enter no. of mules
5
1.6400000000000001 0.0 3.36 

Propotional mule distribution as
Cluster 1= 1
Cluster 2= 0
Cluster 3= 4

Initial mules location
mule 1 -> 4
mule 2 -> 8
mule 3 -> 8
mule 4 -> 8
mule 5 -> 8

Path of each mule
[4, 3, 7, 4]
[8, 10, 6, 8]
[8, 9, 8]
[8, 2, 8]
[8, 1, 8]

Enter velocity(km/h) of DM
3

mule 6 having highest latency cost, hence overall latency of the scnerio is = 167.99999999999997 seconds


Process finished with exit code 0

