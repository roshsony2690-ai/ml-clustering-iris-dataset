Clustering Analysis on Iris Dataset

📋 Overview
This project implements and compares two popular clustering algorithms - KMeans and Hierarchical Clustering - on the classic Iris dataset. The goal is to identify natural groupings in the data without using label information, demonstrating the power of unsupervised learning techniques.

🎯 Objective

The main objectives of this project are:

• Apply unsupervised learning techniques to cluster the Iris dataset    
• Understand and implement KMeans clustering algorithm               
• Understand and implement Hierarchical clustering algorithm           
• Compare the performance of both algorithms                         
• Visualize clustering results and interpret findings           

📊 Dataset
The Iris dataset is a multivariate dataset introduced by Ronald Fisher in 1936. It contains:

150 samples with 50 samples from each of three species of Iris flowers

4 features: sepal length, sepal width, petal length, and petal width (all in cm)

3 species: setosa, versicolor, and virginica

Note: For clustering purposes, the species labels are only used for evaluation, not during the clustering process.

🛠️ Technologies Used
Python 3.x

Libraries:

numpy & pandas - Data manipulation

matplotlib & seaborn - Data visualization

scikit-learn - Machine learning algorithms and metrics

scipy - Hierarchical clustering and dendrograms

📁 Project Structure
text
├── clustering_analysis.ipynb     # Main Jupyter notebook with complete analysis
├── README.md                     # Project documentation
└── requirements.txt              # Required Python packages

🔍 Key Features
1. Data Preprocessing
Loading dataset from sklearn

Exploratory Data Analysis (EDA)

Feature standardization for optimal clustering performance

Missing value check and data validation

2. KMeans Clustering
Algorithm explanation: Detailed description of how KMeans works

Optimal K selection: Elbow method and silhouette scores

Cluster visualization: 2D scatter plots for all feature combinations

Centroid visualization: Marking cluster centers on plots

Performance metrics: Adjusted Rand Index and Normalized Mutual Information

3. Hierarchical Clustering
Algorithm explanation: Agglomerative vs Divisive approaches

Linkage methods comparison: Ward, Complete, Average, Single

Dendrogram visualization: Tree-like hierarchy of clusters

Cluster visualization: 2D scatter plots for all feature combinations

Performance metrics: Comparison with actual labels

4. Comparative Analysis
Side-by-side comparison of both algorithms

• Quantitative performance metrics

• Visual comparison with actual species

• Discussion of strengths and limitations

📈 Results Summary
Metric	                |  KMeans Clustering 	 |  Hierarchical Clustering  |
------------------------|----------------------|---------------------------|
Adjusted Rand Index 	  |  ~0.73               |  ~0.73                    |
Normalized Mutual Info  |	~0.76   	           |  ~0.76                    |
Optimal Clusters	      |  3   	               |  3                        |

Both algorithms successfully identified the three natural groupings in the Iris dataset, with strong agreement with the actual species labels.
