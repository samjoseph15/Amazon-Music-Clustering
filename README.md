# 🎵 Amazon Music Clustering

## 📌 Project Overview
This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to group Amazon Music songs based on their audio characteristics. By analyzing features such as danceability, energy, loudness, tempo, acousticness, and valence, the model identifies songs with similar musical patterns without using predefined genre labels.

## 🎯 Objectives
- Explore and preprocess the music dataset.
- Select relevant audio features for clustering.
- Normalize the data using StandardScaler.
- Apply the K-Means clustering algorithm.
- Evaluate clustering performance using Silhouette Score and Inertia.
- Visualize clusters using Principal Component Analysis (PCA).

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset
The dataset contains audio features of Amazon Music tracks, including:
- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Duration

## 📊 Project Workflow
1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Feature Selection
4. Data Scaling
5. K-Means Clustering
6. Cluster Evaluation
7. PCA Visualization
8. Result Analysis

## 📈 Results
The K-Means model successfully grouped songs into meaningful clusters based on their audio features. PCA was used to reduce the dataset into two dimensions, making it easier to visualize and interpret the clusters.

## 📁 Project Structure

```
Amazon-Music-Clustering/
│── Amazon_Music_Clustering.ipynb
│── dataset.csv
│── README.md
│── requirements.txt
```

## 🚀 Future Enhancements
- Implement DBSCAN and Hierarchical Clustering for comparison.
- Develop a music recommendation system using cluster labels.
- Build a Streamlit web application for interactive visualization.

## 👨‍💻 Author
**George**
