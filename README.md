# CryptoClustering
This CryptoClustering project utilizes unsupervised learning techniques to analyze and cluster cryptocurrency market data. The project focuses on applying K-means clustering and Principal Component Analysis (PCA) to identify patterns and groupings within the cryptocurrency market based on price changes.

Summary of Steps:
Data Preparation:
The project began with loading and exploring the provided "crypto_market_data.csv" file to understand the structure of the data.

Standardization:
The data was standardized using the StandardScaler module from scikit-learn to ensure that all features were on the same scale.

Principal Component Analysis (PCA):
PCA was used to reduce the dimensionality of the original scaled data and extract the most significant features.

Finding the Best Value for k (Original Data and PCA Data):
The elbow method was employed to determine the optimal number of clusters (k) for the original scaled data and the reduced PCA data.

Clustering Cryptocurrencies with K-means (Original Data and PCA Data):
The K-means algorithm was applied using the optimal value of k determined from the elbow method, and the cryptocurrencies were clustered accordingly.

Visualizing and Comparing the Results:

Composite plots were created to compare the elbow curves and cryptocurrency clusters obtained from the original data and the PCA data.

Conclusion:
The analysis revealed insights into the grouping and patterns within the cryptocurrency market. By employing both K-means clustering and PCA, the project showcased how unsupervised learning techniques can aid in understanding complex datasets and identifying underlying structures within the cryptocurrency market. The result of using PCA vs. the original data resulted in more concentrated clusters, which can provide more insight even though its a reduced dataset.
