# K-Means Clustering on Customer Dataset

This project applies K-Means clustering on a customer dataset to segment customers based on their age and spending score.

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Setup Instructions](#setup-instructions)  
- [Implementation Steps](#implementation-steps)  
- [Usage](#usage)  
- [Results](#results)  
- [License](#license)  

## Overview

The goal of this project is to apply K-Means clustering to a customer dataset and group individuals based on their spending patterns and demographics. The dataset consists of attributes like customer ID, age, gender, income, and spending score. This project will analyze customer behaviors and visualize clusters in a 2D space.

## Dataset

The dataset used in this project can be downloaded from the following link:  
[**Customer Dataset**](https://t.ly/DW1KA)  

## Implementation Steps

1. **Load the Dataset**  
   - Read the dataset using Pandas and explore its structure.  
   - Check for missing values and handle them if necessary.  

2. **Data Preprocessing**  
   - Normalize the numerical features if needed.  
   - Select relevant features (e.g., Age and Spending Score) for clustering.  

3. **Apply K-Means Clustering**  
   - Use the **Elbow method** and **Silhouette score** to determine the optimal number of clusters (K).  
   - Fit the K-Means model to the selected features.  

4. **Visualize Clusters**  
   - Plot a 2D scatter plot with different clusters highlighted in distinct colors.  
   - Mark centroids for better visualization.  

## Usage

1. **Run the Clustering Script**  
   Execute the Python script to run the clustering model:  
   ```bash
   python kmeans_clustering.py
   ```

2. **Modify the Number of Clusters**  
   To change the number of clusters, modify the `n_clusters` parameter inside `kmeans_clustering.py`:
   ```python
   kmeans = KMeans(n_clusters=5, random_state=42)
   ```

3. **Visualize the Results**  
   The script will generate a 2D scatter plot showing the clustered customer segments.

## Results

- The dataset is grouped into distinct clusters based on age and spending behavior.  
- Customers with similar spending patterns are categorized together, allowing businesses to target specific groups effectively.  
- The Elbow method and Silhouette score help identify the optimal number of clusters.  

📌 Course: ISB46703 Principle of Artificial Intelligence
📌 Lecturer: Sir Ahmad Zhafri Hariz bin Roslan

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
