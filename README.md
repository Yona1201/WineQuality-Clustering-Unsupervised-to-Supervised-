# WineQuality-Clustering-Unsupervised-to-Supervised

Proyek ini menggunakan pendekatan dua tahap untuk memprediksi kualitas anggur dengan menggabungkan Unsupervised Learning (clustering) dan Supervised Learning  (klasifikasi).

## Deskripsi Singkat
1. **Clustering (Unsupervised Learning)**:
   - **KMeans Clustering**: Dataset dikelompokkan menggunakan KMeans untuk membuat label kualitas.
   - **Pemilihan Jumlah Cluster**: Menggunakan Metode Elbow dan Silhouette Score.

2. **Klasifikasi (Supervised Learning)**:
   - **Random Forest Classifier**: Cluster yang terbentuk digunakan sebagai label untuk melatih model Random Forest, memprediksi kualitas anggur berdasarkan fitur fisikokimia.

## Dataset
Dataset dapat diunduh dari Kaggle: [Wine Dataset for Clustering](https://www.kaggle.com/datasets/harrywang/wine-dataset-for-clustering/data).

## Langkah-Langkah
1. **Persiapan**: Instal library yang diperlukan: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
2. **Clustering**: Jalankan file `wine_quality_clustering.ipynb` untuk menghasilkan label.
3. **Klasifikasi**: Gunakan file `wine_quality_classification.ipynb` untuk melatih dan mengevaluasi model Random Forest.

## Hasil
- **Clustering**: Menggunakan 3 cluster untuk mewakili kualitas anggur.
- **Evaluasi Klasifikasi**: Akurasi, presisi, recall, dan F1-score menunjukkan performa model dalam memprediksi kualitas anggur.

## Kesimpulan
Pendekatan ini memungkinkan klasifikasi kualitas anggur saat data label awal tidak tersedia, menunjukkan potensi kombinasi pembelajaran tanpa pengawasan dan terawasi.

