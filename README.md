🛍️ SkillCraft Machine Learning Internship – Task 02

This repository contains my completed submission for Task 02 of the SkillCraft Machine Learning Internship, where I implemented KMeans Clustering to segment mall customers based on their demographics and spending behavior.

📌 Problem Statement

Use unsupervised learning techniques to segment customers based on the following features:

Age

Annual Income (k$)

Spending Score (1–100)

Objective:Identify natural groupings of customers to help the business with targeted marketing strategies.

Dataset:Provided by SkillCraft under the "Mall Customer Segmentation" category.

📊 Workflow Summary

✅ Data Preprocessing

Loaded and inspected dataset using Pandas

Scaled numerical features using StandardScaler

Selected relevant features: Age, Income, Spending Score

✅ Exploratory Data Analysis

Plotted Age vs Spending Score using Seaborn

Analyzed customer patterns with scatterplots and heatmaps

✅ Optimal Clusters - Elbow Method

Calculated WCSS for k = 1 to 10

Identified optimal number of clusters (k = 5) using the elbow curve

✅ KMeans Clustering

Applied KMeans with n_clusters = 5

Labeled each customer with a cluster ID

✅ Cluster Visualization

Plotted Annual Income vs Spending Score colored by cluster

Saved visual output as kmeans_clusters.png

🧠 Key Learnings

Hands-on experience with unsupervised learning

Practical use of the Elbow Method to determine optimal k

Importance of data scaling in clustering

Visualizing high-dimensional data for interpretation

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Notebook: Jupyter / Google Colab

📁 Files Included

SCT_ML_2.ipynb: Complete notebook with data analysis, clustering, and visualization

kmeans_clusters.png: Saved image of customer clusters

📬 Connect

Feel free to explore the project, give feedback, or connect for collaboration!
https://www.linkedin.com/in/bhanu-tavva-880030367/

