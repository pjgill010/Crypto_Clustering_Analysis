# Crypto_Clustering_Analysis
This project utilizes unsupervised machine learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

### Summary:
- Find the Best Value for k by Using the Original Data
- Cluster the Cryptocurrencies with K-Means by Using the Original Data
- Optimize the Clusters with Principal Component Analysis
- Find the Best Value for k by Using the PCA Data
- Cluster the Cryptocurrencies with K-means by Using the PCA Data
- Visualize and Compare the Results

### Questions:
- What is the best value for k? Answer: 4
- What is the total explained variance of the three principal components? Answer: 89.5%
- What is the best value for k when using the PCA data? Answer: 4
- Does it differ from the best k value found using the original data? Answer: No difference
- What is the impact of using fewer features to cluster the data using K-Means? Answer: Having fewer features does not necessarily mean significat impact for this comparison. Fewer features may result in less accurate clusters as we are missing 10.5% of the variance in data. 
### Original Elbow
![8](https://user-images.githubusercontent.com/118948437/234167714-685ed916-9be2-4772-8cda-ccdc8adc36f4.png)
### PCA Elbow
![9 pca](https://user-images.githubusercontent.com/118948437/234167914-09db57d6-4e18-46ab-b2ab-2bb513de0ce5.png)
### Original Scatter
![10](https://user-images.githubusercontent.com/118948437/234165688-6b275e2b-00e3-43e7-8ae4-1342c635b17b.png)
### PCA Scatter
![11](https://user-images.githubusercontent.com/118948437/234165699-9224c84f-5c35-4b2c-b35e-c90880fe2061.png)
