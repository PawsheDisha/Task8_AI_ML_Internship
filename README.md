# Task8_AI_ML_Internship

#  K-Means Clustering Implementation



##  Objectives

1. Load and preprocess dataset  
2. Visualize dataset (optional PCA for 2D view)  
3. Apply K-Means clustering  
4. Determine optimal number of clusters using Elbow Method  
5. Visualize clusters with color-coding  
6. Evaluate clustering performance using Silhouette Score  


##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  



##  Steps Performed

### 1️. Import Required Libraries
Essential libraries for data manipulation, visualization, and clustering are imported.

### 2️. Load Dataset
The dataset is loaded using Pandas.  
Non-numeric columns are removed since K-Means works only with numerical data.

### 3️. Data Standardization
Data is scaled using `StandardScaler` to ensure equal contribution of all features.

### 4️. Elbow Method
The Elbow Method is used to determine the optimal number of clusters (K).  
WCSS (Within Cluster Sum of Squares) is calculated for K = 1 to 10.

### 5️. Apply K-Means
K-Means algorithm is applied using the optimal K value.  
Cluster labels are assigned to each data point.

### 6️. PCA Visualization
Principal Component Analysis (PCA) reduces data to 2 dimensions for visualization.  
Clusters are displayed using color coding.

### 7️. Silhouette Score
Silhouette Score evaluates clustering performance:
- Close to **1** → Well-separated clusters  
- Around **0** → Overlapping clusters  
- Negative → Poor clustering  



##  Conclusion

This project successfully demonstrates how to implement and evaluate K-Means clustering.  
It helps in understanding how unsupervised learning groups similar data without labeled outputs.
