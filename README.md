
Gemini said
Budur, təqdim etdiyiniz Iris təsnifatı layihəsi üçün ingilis dilində hazırlanmış README.md faylı:

Iris Species Classification & Clustering
This project focuses on the classification and clustering of the classic Iris dataset. It utilizes various machine learning techniques including K-Means, Hierarchical Clustering, and Principal Component Analysis (PCA) to group and identify different iris species based on their morphological features.

Project Description
The goal of this project is to explore unsupervised learning methods to partition the Iris dataset into distinct groups. By analyzing sepal and petal measurements (length and width), the models attempt to rediscover the biological species categories without prior labels, and then compare these results with actual species data.

Features & Workflow
Data Preprocessing: Loading data via pandas and encoding categorical species labels using LabelEncoder.

K-Means Clustering: Implementing the K-Means algorithm to partition the data into 3 clusters.

Hierarchical Clustering: Using the linkage (Ward's method) and dendrogram techniques to visualize and identify clusters.

Dimensionality Reduction (PCA): Reducing the feature space to visualize high-dimensional data in a 2D plot.

Performance Evaluation: Comparing cluster assignments with ground truth labels using Confusion Matrices.

Visualization: Using matplotlib and seaborn to create insightful plots of the clustering results.

Technologies Used
Python

Pandas

Scikit-learn (KMeans, PCA, LabelEncoder)

Scipy (Hierarchical clustering)

Matplotlib & Seaborn (Data Visualization)

Dataset
The dataset used is the Iris dataset, which contains 150 samples of iris flowers from three different species:

Iris-setosa

Iris-versicolor

Iris-virginica

Each sample has four features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)
