# Tugas Besar: Analisis Prediktif Data Kesehatan (Cardiovascular Disease)

Proyek ini adalah implementasi sistem kecerdasan buatan (*Artificial Intelligence*) dan pengolahan *Big Data* untuk memprediksi risiko penyakit kardiovaskular pada pasien berdasarkan data rekam medis.

## Deskripsi Singkat
Proyek ini menggunakan dataset rekam medis sebesar 70.000 data untuk melatih model klasifikasi dalam memprediksi status kesehatan pasien (positif/negatif risiko penyakit jantung). Kami menggunakan **Apache Spark (PySpark)** untuk menangani pemrosesan data skala besar dan **Random Forest Classifier** sebagai mesin prediksi utama.

## Teknologi yang Digunakan
- **Big Data Engine:** Apache Spark (via PySpark)
- **Machine Learning Library:** Spark MLlib
- **Data Manipulation:** Pandas & PySpark DataFrame
- **Visualization:** Matplotlib
- **Environment:** Google Colab

## Cara Menjalankan Proyek
1. **Persiapan Data:**
   - Unduh dataset [Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) dari Kaggle.
   - Unggah file `cardio_train.csv` ke dalam folder penyimpanan di Google Colab.
2. **Eksekusi:**
   - Buka file `FinalProject.ipynb` di Google Colab.
   - Pastikan *runtime* sudah aktif.
   - Klik menu **Runtime > Run all** untuk menjalankan seluruh alur dari *loading* data hingga visualisasi hasil.
3. **Hasil:**
   - Model akan menghasilkan metrik akurasi dan grafik batang (*bar chart*) yang menunjukkan faktor medis paling dominan terhadap risiko penyakit jantung.

## Dokumentasi Tambahan
Untuk penjelasan mendalam mengenai metodologi, analisis, dan interpretasi hasil, silakan merujuk pada dokumen laporan resmi di tautan berikut:
https://drive.google.com/file/d/1E9pMV7CSYV0P4p_1hTBQYuaMq2bZrDjh/view?usp=sharing

LINK VIDEO PRESENTASI

