# Clustering Pelanggan UK-Based Online Retail Industry Menggunakan K-Means dan RFM Analysis

## Deskripsi Singkat Proyek dan Latar Belakang Masalah

Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan perilaku belanja mereka menggunakan analisis RFM (Recency, Frequency, Monetary) dan algoritma K-Means. Segmentasi pelanggan merupakan hal penting dalam dunia bisnis untuk mengoptimalkan strategi pemasaran. Dengan membagi pelanggan menjadi beberapa klaster berdasarkan pola interaksi mereka, perusahaan dapat merancang pendekatan yang lebih personal dan efektif dalam mempertahankan serta meningkatkan loyalitas pelanggan.

## Penjelasan Dataset

Dataset yang digunakan adalah **Online Retail** dari UCI Machine Learning Repository. Dataset ini berisi transaksi e-commerce yang terjadi antara 2010 dan 2011 di sebuah perusahaan retail Inggris. Setiap transaksi mencakup atribut seperti tanggal transaksi, jumlah, harga satuan, dan ID pelanggan. Dataset ini digunakan untuk menghitung metrik RFM tiap pelanggan.

## Algoritma yang Digunakan

- **K-Means**: Digunakan sebagai algoritma klastering untuk mengelompokkan pelanggan berdasarkan nilai RFM yang telah dinormalisasi.
- **PCA (Principal Component Analysis)**: Digunakan untuk mereduksi dimensi fitur guna visualisasi klaster secara dua dimensi.
- **Silhouette Score**: Digunakan sebagai metrik evaluasi kualitas klastering.

## Panduan Menjalankan Kode

1. **Pastikan struktur folder seperti berikut:**

![image](https://github.com/user-attachments/assets/d2339690-a66e-4a23-8c54-ef33ed82e2c6)


2. **Install dependensi:**

3. Buka notebook:
cd notebooks
jupyter notebook kmean.ipynb

4. Pastikan file dataset tersedia di path berikut:
../data/Online Retail.xlsx

### Contoh Hasil Output dan Visualisasi
![output2](https://github.com/user-attachments/assets/cb4e3252-22f2-4dab-b5e7-af40de1acf9f)

Heatmap RFM tiap klaster menunjukkan perbedaan karakteristik masing-masing segmen pelanggan.

## Kesimpulan
Model K-Means berhasil mengelompokkan pelanggan ke dalam empat segmen berdasarkan nilai RFM. Hasil ini menunjukkan segmentasi yang cukup jelas dan berguna untuk strategi pemasaran terfokus. Analisis ini dapat dikembangkan lebih lanjut dengan menambahkan variabel lain atau menggunakan algoritma klastering yang berbeda.
