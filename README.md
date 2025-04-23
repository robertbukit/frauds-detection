# 🕵️‍♂️ Frauds Detection - Clustering & Classification

Proyek ini berfokus pada deteksi fraud (kecurangan) dengan pendekatan unsupervised dan supervised learning. Dalam proyek ini, dilakukan dua pendekatan utama:

1. **Clustering (Unsupervised Learning)** untuk mengidentifikasi pola-pola anomali tanpa label fraud.
2. **Classification (Supervised Learning)** untuk membangun model prediksi berdasarkan data yang telah dilabeli.

### 🧩 Clustering
Clustering dilakukan untuk mendeteksi potensi fraud dalam data tanpa label menggunakan:
- Encoding data kategorial
- Standarisasi data
- KMeans Clustering
- Evaluasi dengan **Silhouette Score**
- Eksperimen jumlah cluster dengan **Elbow Method**
- Visualisasi hasil clustering untuk interpretasi
- DBSCAN Clustering
- Label mapping cluster DBSCAN
- Visualisasi 2D PCA dan interpretasi hasil

### ✅ Classification
Model klasifikasi dilatih untuk mendeteksi fraud dengan label menggunakan:
- Pembagian data training/testing
- Algoritma  **Random Forest** dan **SVM**
- Evaluasi performa dengan **accuracy**, **precision**, **recall**, dan **f1-score**

---

## 📊 Tools dan Library
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn
