# Zaneta_Nogacz_Portfolio


#Data Science Project: Customer Segmentation - Overview
* Created a template for segmentation analysis
* Dataset contains information about bank customers (this is training dataset provided by tutor in csv file)
* Dataset were cleaned,  


###Motivation
Marketing is a filar for growth and sustainability of any business. Knowlege about markets and customers is crucial for any strategic decisions, which can create a strong brand and increase sales.
Segmentation is one the most important application of unsupervised learning. Using clustering techniques, companies can identify groups of customers allowing them to understand customers behaviour and recognize a target of marketing capain. In this machine learning project, I applied K-Means clustering, which is the essential algorithm for clustering of unlabeled dataset. Then performed Principal Component Analysis for dimentions recuction. Finally, as a comparisson, I build  Autoencoder based on Arfificial Neuronal Networks in order to reduce features and then perform again KMeans clustering and PCA.

#### Keywords: K-Means, 'Elbow Method', Principal Component Analysis (PCA), Autoencoder

## Outline

1. Importing libraries and dataset

2. Data cleaning
2.1. Checked extreem values
2.2. Dealed with missing values
2.3. Checked of duplicated records

3. Features exploration, visualisation and scaling
3.1. Features exploration and vizualization
3.2. Correlations: calculation and visualization
3.3. Data scaling

4. 'Elbow Method' - selecting the optimal number of clusters
4.1. WCSS calculation
4.2. Plot of WCSS vs. clusters

5. K-Means Method - application
5.1. Applicaction of K-Means algorithm for 8 clusters
5.2. Table of cluster centres with values of fearures specific for each cluster
5.3. Inversion of scaled data into orginal data
5.4. Characteristics of clusters – table
5.5. Descriptions of main customer segments
5.6. Concatanating cluster labes to original dataset
5.7. Histograms of various clusters

6. Principal Component Analysis (PCA)
6.1. Calculation of 2 Principal components
6.2. Vizualisation of clusters after PCA

7. Autoencoder
7.1. Creating Artificial Neuron Networks (ANN)
7.2. Copressing data with ANN
7.3. Application of 'Elbow Method'
7.4. Application KMeans for 4 clusters
7.5. Application of PCA on compressed data. (2 principal components)
7.6. Visualization of 4 predicted clusters in 2D space
7.7. Vizualisation of 4 clusters with corresponding features values (histograms)

8. Conclusion






