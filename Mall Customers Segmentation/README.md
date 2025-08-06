# 🛍️ Customer Segmentation using K-Means Clustering

This project uses **K-Means Clustering** to segment customers based on their **Annual Income** and **Spending Score** using the **Mall Customers dataset**. The goal is to identify distinct customer groups to help businesses understand customer behavior and target marketing strategies effectively.

---

## 📁 Dataset

- **File:** `Mall_Customers.csv`
- **Features:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🔍 Steps Involved

### 1️⃣ Import Libraries
Essential Python libraries for data manipulation, visualization, and machine learning are imported.

### 2️⃣ Load Dataset
The dataset is loaded using **Pandas**, and a preview is shown using `.head()`.

### 3️⃣ Data Exploration
- Checked data types
- Verified missing values
- Explored descriptive statistics using `.info()` and `.describe()`

### 4️⃣ Data Preprocessing
- Dropped irrelevant columns: `CustomerID`, `Gender`
- Normalized data using `StandardScaler`

### 5️⃣ Optimal K Value (Silhouette Score Method)
- Tested K values from 2 to 10 using **silhouette score**
- ✅ Best score observed at **k = 6**

### 6️⃣ Training K-Means Model

```python
from sklearn.cluster import KMeans

kmeans = KMeans(n_clusters=5, init='k-means++', random_state=42)
clusters = kmeans.fit_predict(X_scaled)
df['Cluster'] = clusters
``` 
### 7️⃣ Visualizing Clusters
Used Seaborn to plot clusters based on:

Annual Income (k$)

Spending Score (1–100)

### 8️⃣ PCA for 2D View
Applied Principal Component Analysis (PCA) to reduce dimensionality

Visualized clusters in 2D for better interpretation

### 📊 Output
## 📌 Cluster Plot
Visualizes how customers are grouped based on income and spending habits.

## 📌 PCA View
Shows the clustering performance after dimensionality reduction.

## 🧠 Insights
The model segments customers into distinct behavioral clusters.

Enables targeted marketing and personalized strategies.

###✅ Requirements
Install all necessary libraries using:

bash
pip install pandas numpy matplotlib seaborn scikit-learn

### 📌 Project Status
✔️ Completed

📊 Visualized

📦 Ready for deployment or further enhancements (e.g., web integration, dashboards)

### 🙋‍♀️ Author
## Akshada Sondekar
🎓 BCA AIML Student | Machine Learning Enthusiast

Edit
