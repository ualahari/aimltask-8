# aimltask-8
Task 8: Clustering with K-Means
# 📊 K-Means Clustering – Customer Segmentation

## 📌 Objective
Perform **unsupervised learning** with **K-Means clustering** to group customers into distinct segments based on their attributes.  
This project demonstrates:
- Clustering  
- Elbow Method  
- Silhouette Score  
- Visualization of clusters  

---

## 🛠 Tools & Libraries
- Python 3  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Google Colab (for running & uploading dataset)  

---

## 📂 Dataset
- **Mall Customers Dataset** (Kaggle)  
- Features used:  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`  

*(You can replace with any other Kaggle dataset by uploading a CSV file.)*  

---

## 🚀 Steps Implemented
1. **Upload Dataset** → User uploads a Kaggle `.csv` file.  
2. **Data Preprocessing** → Selected features and standardized them.  
3. **Elbow Method** → Determined optimal `k` (number of clusters).  
4. **Fit K-Means** → Assigned each customer to a cluster.  
5. **Visualization** → Scatter plot with cluster color coding and centroids.  
6. **Evaluation** → Used **Silhouette Score** to measure clustering quality.  
7. **Save Results** → Exported clustered dataset to `clustered_dataset.csv`.  

---

## 📊 Results
- **Optimal K** (from Elbow Method): `5`  
- **Silhouette Score**: `0.55` (shows good separation between clusters)  
- Clear customer segmentation observed in 2D visualization.  

---

## 📸 Visualizations
- Elbow Method plot  
- K-Means cluster scatter plot with centroids  

*(Screenshots can be added in a `/screenshots` folder.)*  

---

## 📁 Repository Contents
- `kmeans_clustering.ipynb` → Jupyter Notebook with code  
- `README.md` → Documentation (this file)  
- `clustered_dataset.csv` → Output file with cluster labels  
- `screenshots/` → Cluster plots (optional)  

---

## ✅ How to Run
### 🔹 Google Colab
1. Open the notebook in **Google Colab**.  
2. Upload your Kaggle dataset (`Mall_Customers.csv` or any other).  
3. Run all cells.  
4. The clustered dataset will be saved as `clustered_dataset.csv`.  

### 🔹 Local Setup
```bash
git clone https://github.com/your-username/KMeans-Clustering-Task.git
cd KMeans-Clustering-Task
pip install -r requirements.txt
jupyter notebook kmeans_clustering.ipynb
