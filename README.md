# K-Means

## 📌 Objective
Perform unsupervised learning using **K-Means Clustering** on the Mall Customers dataset.

---

## 📂 Dataset
Mall_Customers.csv (Customer income, spending score)

---

## 🔧 Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-Learn

---

## 📝 Steps Performed
### 1️⃣ Load Dataset  
Read the CSV file and selected 2 numeric features:
- Annual Income  
- Spending Score  

### 2️⃣ Data Preprocessing  
Scaled the selected features using **StandardScaler**.

### 3️⃣ Elbow Method  
Plotted K vs Inertia to find optimal number of clusters (best K ≈ **5**).

### 4️⃣ K-Means Model  
Fitted KMeans with `n_clusters=5` and assigned cluster labels.

### 5️⃣ Evaluation  
Calculated **Silhouette Score** → Measures clustering quality.

### 6️⃣ Visualization  
Displayed cluster scatter plot with color-coding.

---

## 📊 Results
- Optimal clusters: **5**
- Good variation and separation between customer segments.
- Useful for customer segmentation in marketing.



