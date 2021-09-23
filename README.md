# College-Clustering-Using-K-Means
Overview

Clustering is one of the most common exploratory data analysis technique used to get an intuition about the structure of the data. It can be defined as the task of identifying subgroups in the data such that data points in the same subgroup (cluster) are very similar while data points in different clusters are very different. In other words, we try to find homogeneous subgroups within the data such that data points in each cluster are as similar as possible according to a similarity measure such as euclidean-based distance or correlation-based distance. The decision of which similarity measure to use is application-specific.
Clustering analysis can be done on the basis of features where we try to find subgroups of samples based on features or on the basis of samples where we try to find subgroups of features based on samples. We’ll cover here clustering based on features. Clustering is used in market segmentation; where we try to find customers that are similar to each other whether in terms of behaviors or attributes, image segmentation/compression; where we try to group similar regions together, document clustering based on topics, etc.
Unlike supervised learning, clustering is considered an unsupervised learning method since we don’t have the ground truth to compare the output of the clustering algorithm to the true labels to evaluate its performance. We only want to try to investigate the structure of the data by grouping the data points into distinct subgroups.

K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of predefined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on.
It allows us to cluster the data into different groups and a convenient way to discover the categories of groups in the unlabeled dataset on its own without the need for any training.
It is a centroid-based algorithm, where each cluster is associated with a centroid. The main aim of this algorithm is to minimize the sum of distances between the data point and their corresponding clusters.

Proposed Methodology

Dataset:
This is given to us and we already have the csv file that we will be using for dataset model.
<img width="602" alt="Screenshot 2021-09-23 at 8 50 43 PM" src="https://user-images.githubusercontent.com/85802579/134535804-a089be96-f896-420f-a616-9e3df8043ebd.png">


Data Pre-Processing: 
A real-world data generally contains noises, missing values, and maybe in an unusable format which cannot be directly used for machine learning models. Data preprocessing is required tasks for cleaning the data and making it suitable for a machine learning model which also increases the accuracy and efficiency of a machine learning model.

<img width="530" alt="Screenshot 2021-09-23 at 8 51 00 PM" src="https://user-images.githubusercontent.com/85802579/134535838-bb26e846-df68-4e95-bfb4-dc68331688df.png">

3. Algorithm used:  
K-means clustering is a very famous and powerful unsupervised machine learning algorithm. It is used to solve many complex unsupervised machine learning problems. Before we start, let's take a look at the points which we are going to understand.


4. Model Building: 
The data are then divided into 2 clusters since there are two types of colleges (i.e govt and private) that we have to separate. 

5. Model Evaluation:. 
Model evaluation aims to estimate the generalization accuracy of a model on future (unseen/out-of-sample) data.So our accuracy was about 80%.


Visualization

1.Scatterplot between Grad.rate vs Room.Board
<img width="521" alt="Screenshot 2021-09-23 at 8 51 58 PM" src="https://user-images.githubusercontent.com/85802579/134536000-3fb363c8-cca0-4f82-bc07-7ee8bfc60eb9.png">

2.Scatterplot between F.Undergraduate and Outstate
<img width="620" alt="Screenshot 2021-09-23 at 8 52 19 PM" src="https://user-images.githubusercontent.com/85802579/134536074-6f743fa3-7f44-458d-b1bd-8b2b712191fb.png">

3.Tution fee variation 

<img width="627" alt="Screenshot 2021-09-23 at 8 52 37 PM" src="https://user-images.githubusercontent.com/85802579/134536135-132d5854-51a3-4cf8-8a12-82285e2f060e.png">


4. Graduation Rate 

<img width="618" alt="Screenshot 2021-09-23 at 8 52 57 PM" src="https://user-images.githubusercontent.com/85802579/134536186-b92e3341-f9d8-4124-8f0e-fe1d8a422d6f.png">

Implementation 



Importing Libraries

<img width="534" alt="Screenshot 2021-09-23 at 8 53 37 PM" src="https://user-images.githubusercontent.com/85802579/134536322-b8f4229a-5a0b-4e5c-9cd5-4b2d2d25521a.png">


<img width="566" alt="Screenshot 2021-09-23 at 8 53 59 PM" src="https://user-images.githubusercontent.com/85802579/134536380-b8793ae1-972c-4f6a-aa51-b6674e9f37f2.png">


<img width="566" alt="Screenshot 2021-09-23 at 8 54 08 PM" src="https://user-images.githubusercontent.com/85802579/134536403-8e7ed9e4-958d-4b44-bd44-8117399d78a3.png">



<img width="497" alt="Screenshot 2021-09-23 at 8 54 20 PM" src="https://user-images.githubusercontent.com/85802579/134536440-110647e8-a7b9-4fd4-a010-3f3b78aad154.png">

Conclusion 

We have successfully separated the college based on the private or public using K-Means clustering.
The data was given to us and we’ve built a model which will divide the college based on the type of institute[‘government’,’private’]









