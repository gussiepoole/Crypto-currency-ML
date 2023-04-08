# Crypto-currency-ML
A project using unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes

•	In this project I coded the elbow method algorithm to find the best value for k using the original data and then the scaled data

•	Predicting the clusters to group the cryptocurrencies of both unscaled and scaled data demonstrated the importance of preprocessing and scaling data      before feeding it an agorythem.

•	I optimized the clusters with Principal Component Analysis (PCA) to to reduce the features to three principal component

•	In this project 90% of the total variance is condensed into the 3 PCA variables


<img width="440" alt="Screenshot 2023-04-08 at 13 07 25" src="https://user-images.githubusercontent.com/115706722/230727051-63b5762c-8c22-48f4-b419-adf8ba473cf8.png">

**An insight into the septs in this process:**

•	Use the `StandardScaler()` module from scikit-learn to normalize the data from the CSV file

<img width="679" alt="Screenshot 2023-04-08 at 13 05 42" src="https://user-images.githubusercontent.com/115706722/230720141-9a970ed9-edb4-4fb8-9c88-878b604d4f46.png">

•	I plotted a ine chart of all the inertia values computed with the different values of k, in order to visually identify the optimal value for k
