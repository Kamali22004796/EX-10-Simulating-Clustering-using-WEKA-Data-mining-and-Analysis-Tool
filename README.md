# EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool
# DATE : 5/10/23
# AIM :
To perform a classification technique using WEKA tool.

# WEKA :
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/a1a70461-4b37-44d5-aa08-724803be8406)


# CLUSTERING :
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group." It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns. It is an unsupervised learning method, hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset.
# PROCEDURE :
1.In the WEKA explorer select the Preprocess tab. Click on the Open file ... option and select the iris.arff file in the file selection dialog.

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/20325413-75ea-47a5-8f84-e74ae0c629c4)


2.Click on the Cluster TAB to apply the clustering algorithms to our loaded data. Click on the Choose button. Now, select EM as the clustering algorithm.

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/6083e7d6-e932-4217-8a06-a3c1749adc68)


3.In the Cluster mode sub window, select the Classes to clusters evaluation option

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/1395a923-8c28-4432-9995-eca78b3f4772)


4.Click on the Start button to process the data. After a while, the results will be presented on the screen.

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/ce333588-6b46-46a4-8db6-c289b5eb08f3)


5.From the output screen, you can observe that − There are 5 clustered instances detected in the database. The Cluster 0 represents setosa, Cluster 1 represents virginica, Cluster 2 represents versicolor, while the last two clusters do not have any class associated with them.

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/1b86db58-c140-4241-81cf-168b2d2da192)


6.To visualize the clusters, right click on the EM result in the Result list.

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/a5eaef10-84b7-431f-8cb9-3fc0c861a399)


7.Select Visualize cluster assignments.

![image](https://github.com/Kamali22004796/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/120567837/a0aff143-996e-4b11-88eb-6c12ab7378d2)


# RESULT :
Thus the simulation of clustering technique has been executed using WEKA tool successfully.
