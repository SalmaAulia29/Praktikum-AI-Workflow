# Praktikum_AI_Workflow
2306143_SALMA AULIA NISA

## Deskripsi Proyek
Proyek ini bertujuan untuk mengimplementasikan konsep kecerdasan buatan (AI) dalam analisis dan prediksi penjualan produk. Dalam proyek ini, dilakukan beberapa tahap utama:

Pembuatan Dataset: Membuat dataset penjualan dalam format CSV dengan informasi produk, jumlah terjual, stok, dan harga satuan.

Pembersihan dan Pengolahan Data: Memproses dataset untuk memastikan data bersih, lengkap, dan siap digunakan dalam model AI.

Pelatihan Model AI: Menggunakan Decision Tree Classifier untuk memprediksi apakah suatu produk perlu restock berdasarkan data penjualan.

Prediksi dan Visualisasi: Menggunakan model yang telah dilatih untuk melakukan prediksi serta membuat visualisasi hubungan antara jumlah terjual, stok, dan keuntungan.

## Instruksi Cara Menjalankan Kode di Google Colab

1. **Buka Google Colab**
   - Kunjungi [Google Colab](https://colab.research.google.com/).
   - Pilih "Unggah" dan unggah file `praktikum_ai.ipynb`.

2. **Menjalankan Notebook**
   - Pastikan semua sel dijalankan satu per satu.
   - Jika ada dependensi tambahan, jalankan perintah di dalam sel kode:
     ```python
     !pip install scikit-learn
     ```

3. Mengakses File di Google Drive (Opsional)
   - Jika data atau model disimpan di Google Drive, hubungkan dengan:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
Pastikan semua dependensi telah terinstal agar kode dapat berjalan dengan lancar. Jika ada kendala, periksa kembali dependensi atau pastikan file telah diunggah dengan benar ke Google Colab.


