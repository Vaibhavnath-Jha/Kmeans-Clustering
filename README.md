# Kmeans-Clustering

Program to visualize K means clustering algorithm without using any data science library.

#### Plots 
Contains Images of different Example dataset

#### Data_generator.py
Python program to generate random blob like data using sckit.learn

### KMeans_General.py
Main code in order to execute Kmeans_algorithm.
The algorithm can be altered to as many centers as user wants. Default is set to 3.

####### note on algorithm:
More number of datapoints, more time the algorithm will take to converge. Some results are:

No. of Datapoints | Time Taken (in mins.)
------------------|-----------------------
200 | 1.2
400 | 2.7
1000 | 9.8
2000 | 26.2

*These results were obtained on a system with following configuration:*
CPU    -> Intel Core i5 - 8285U @ 1.60GHz
Memory -> 8GB RAM
GPU    -> Nvidia Geforce MX150
VRAM   -> 2GB 
