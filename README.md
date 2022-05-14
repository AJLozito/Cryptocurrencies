# Cryptocurrencies

     The purpose of this project was to assess the cryptocurrency market and generate a report that includes the types of cryptocurrencies being traded and develop a classification system to group them as potential product offerings.


## Deliverable 1: Preprocessing the Data for PCA
     In this step, I narrowed down the cryptocurrencies based on a variety of filters. The cryptocurrencies with these characteristics were eliminated:
1.)	Nontraded
2.)	Nonworking algorithms
3.)	Null values
4.)	Nonmined

![image](https://user-images.githubusercontent.com/96176817/168439491-be5253fd-0fe0-420f-9650-5dc1701d7e5d.png)


## Deliverable 2: Reducing Data Dimensions Using PCA
     In this step, I used the Principal Component Analysis (PCA) algorithm to pare the data down to the three best possible principal components that could be used to evaluate the cryptocurrencies.

![image](https://user-images.githubusercontent.com/96176817/168439552-b8346508-2d09-4970-ad12-14f394578d41.png)


## Deliverable 3: Clustering Cryptocurrencies Using K-Means
     In this step, I used my knowledge of the K-means algorithm to create an elbow curve to find the best value for K in the PCA data frame created in Deliverable 2.

![image](https://user-images.githubusercontent.com/96176817/168439583-f77b9692-d711-4cb5-b593-3bf57f0ebb1b.png)

I also ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

![image](https://user-images.githubusercontent.com/96176817/168439599-45afd225-11fc-48ae-85ec-16ceeb8b133c.png)


## Deliverable 4: Visualizing Cryptocurrencies Results
     In this step, I used Plotly Express and hvplot to implement scatter plots to visualize the distinct groups that correspond to the three principal components that I created in Deliverable 2.

![image](https://user-images.githubusercontent.com/96176817/168439668-6c4610cb-0b16-437d-8806-4434e7f2fcfa.png)

I also created a table of tradable currencies.

![image](https://user-images.githubusercontent.com/96176817/168439678-2c631ddc-808b-41d0-af9f-a979af639b09.png)
