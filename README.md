# Cryptocurrencies

## Analysis Overview

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features. This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.

We've used the following methods for the to complete our analysis:

preprocessing the database
reducing the data dimension using Principal Component Analysis
clustering cryptocurrencies using K-Means
visualizing classification results with 2D and 3D scatter plots




## Results

The imported DataFrame before cleaning showed 1252 rows of data:

![204948125-3dd6cc0d-fa05-43de-9398-d01ce800e1ab](https://user-images.githubusercontent.com/109055148/213888547-a0a868a9-4d13-44d0-9a1d-c828c137e5b5.png)

List of tradable cryptocurrencies after cleaning, 532 rows of data:



![204948344-b8463539-e4d1-46d6-a133-2fc67432895d](https://user-images.githubusercontent.com/109055148/213888555-ee4181ec-2eb6-4f90-8098-d6e9952e6fc6.png)


Clustering Cryptocurrencies using K-Means - Elbow Curve

We are using unsupervised machine learning to help us identify clusters of the cryptocurrencies. We produced the following elbow curve below using the K-Means method iterating on k values from 1 to 10.

Running K-Means with k=4


![204948681-a9eb97f8-d36a-4cc2-a128-98022ab055db](https://user-images.githubusercontent.com/109055148/213888560-89664074-6b56-40f1-abc7-d76816cf4ba2.png)


The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

Applying the Principal Component Analysis


![204949248-bf06db9f-fb52-459c-a83d-ae8f4072151a](https://user-images.githubusercontent.com/109055148/213888577-f9b4fcc4-2138-4219-9a65-a2f3c12a7ae6.png)


Visualizing Cryptocurrencies Results with 3D-Scatter plot with clusters



![204949361-d9e2ef7f-7eb8-4509-8113-c2295b9676f0](https://user-images.githubusercontent.com/109055148/213888592-0fa0904f-3769-4011-82b8-959c9e5bb78f.png)

3-D scatter plot was generated using the PCA algorithm, reducing the crytocurrencies dimensions down to three principal components.

Number of Tradable Cryptocurrencies

![204949662-8614d841-23c0-4acf-97a2-a3670be2e031](https://user-images.githubusercontent.com/109055148/213888604-4888f370-0c36-4a1e-90e5-a28893e48513.png)

DataFrame to plot results

![204949753-4f334f2c-956e-4169-aa99-49c0136a8207](https://user-images.githubusercontent.com/109055148/213888610-20024632-3751-4bec-9819-01753a834866.png)

Tradable Cryptocurrencies



![204949863-192b1f52-4880-49eb-b1f7-215d200bb804](https://user-images.githubusercontent.com/109055148/213888617-d64149ec-646e-408d-9863-8ce9bf713390.png)


## Summary 

We've identified the classification of 532 cryptocurrencies based on their feature similarities. Each group will need to be analyzed to determined, performance and potential interest for the investment banks potential clients.

