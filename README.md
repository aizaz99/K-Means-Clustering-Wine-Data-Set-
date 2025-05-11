🍷 K-Means Clustering on Wine Dataset
This project applies K-Means Clustering to the Wine dataset, which includes chemical analysis of wines grown in the same region in Italy but derived from three different cultivars.

The goal is to segment wines into distinct clusters based on their chemical properties, without using the actual class labels.

📊 Dataset Details
Source: Built-in dataset from scikit-learn

Samples: 178 wines

Features: 13 continuous attributes such as:

Alcohol

Malic acid

Ash

Alcalinity of ash

Flavanoids

Color intensity

...and more

🔍 Objectives
Perform feature scaling on numeric attributes

Use the Elbow Method to determine the optimal number of clusters

Apply KMeans clustering

Visualize results using PCA for 2D cluster plotting

Interpret how clusters relate to actual wine classes (optional)

📦 Tools Used
Python

scikit-learn

pandas

numpy

matplotlib

seaborn

🚀 How It Works
Data Loading: Loads the Wine dataset from sklearn.datasets.

Preprocessing:

Features are scaled using StandardScaler for better clustering.

Elbow Method:

WCSS is calculated for clusters ranging from 1 to 10 to find the optimal k.

Clustering:

K-Means is applied using the optimal number of clusters (k=3).

Visualization:

PCA reduces the 13-dimensional data to 2D for clear plotting of clusters.

Each wine is plotted based on its cluster assignment.

📈 Sample Output
An Elbow Curve showing the best number of clusters.

A PCA-based 2D scatter plot of clustered wine samples.

Optionally, compare clusters to the actual wine cultivar labels.

✅ How to Run
You can run this notebook directly on:

Kaggle: Upload the code and run — no data file needed (dataset is built-in).

Google Colab: Just copy-paste the notebook code.

Local Jupyter Notebook: Install scikit-learn, matplotlib, seaborn, and pandas.

🧠 Insights
This project demonstrates how unsupervised learning can reveal natural groupings in data. Even without knowing wine types, the algorithm finds meaningful clusters that often align closely with the original class labels.
