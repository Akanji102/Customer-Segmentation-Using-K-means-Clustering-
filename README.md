# Customer-Segmentation-Using-K-means-Clustering


🛒 Customer Segmentation using K-Means Clustering

A data science project that applies unsupervised machine learning (clustering) to segment customers into distinct groups based on purchasing behavior. This helps businesses understand their customers better, personalize marketing strategies, and boost overall customer satisfaction.

📌 Project Overview

Businesses often deal with large amounts of customer data, but without segmentation, it's difficult to make sense of the patterns. By using K-Means Clustering, we can divide customers into meaningful groups (clusters) and gain insights such as:

Which customers are high spenders

Which customers are loyal

Which customers are likely to churn

This project demonstrates how to implement customer segmentation using clustering on a real-world dataset.

🚀 Key Features

✅ Data preprocessing (cleaning, normalization, scaling)

✅ Optimal cluster selection using Elbow Method & Silhouette Score

✅ Customer grouping using K-Means Clustering

✅ Visualizations in 2D & 3D plots

✅ Actionable business insights

🛠️ Tech Stack

Python 3

Pandas, NumPy (data manipulation)

Scikit-learn (K-Means, scaling, metrics)

Matplotlib, Seaborn (visualizations)

Plotly (interactive clustering plots)

📊 Dataset

Source: Mall Customers Dataset (Kaggle)

Features Used:

CustomerID

Age

Annual Income (k$)

Spending Score (1-100)

🔬 Methodology

Data Preprocessing – handled missing values, scaled features

Exploratory Data Analysis (EDA) – distributions, correlations, spending behavior

Optimal K Selection – used Elbow Method & Silhouette Analysis

Clustering with K-Means – grouped customers into clusters

Visualization & Insights – plotted clusters to understand customer groups

📈 Results & Insights

Identified 5 customer segments:

🟢 High-income, high-spending customers (VIPs)

🔵 High-income, low-spending customers (Potential loyal customers)

🟡 Low-income, high-spending customers (Bargain seekers)

🟣 Average income, average spenders (Mainstream customers)

🔴 Low-income, low-spending customers (Price-sensitive)

These insights can guide personalized marketing, loyalty programs, and product targeting.

📂 Project Structure
📦 Customer-Segmentation-KMeans
 ┣ 📜 README.md
 ┣ 📜 customer_segmentation.ipynb
 ┣ 📜 requirements.txt
 ┣ 📂 data
 ┗ 📂 plots
