# Prediksi Waktu Tidur Berdasarkan Fitur Kesehatan

## Deskripsi

Aplikasi ini memprediksi waktu tidur seseorang berdasarkan beberapa faktor kesehatan seperti usia, jenis kelamin, penyakit fisik, kebiasaan olahraga, penggunaan layar per hari, dan kebiasaan merokok atau minum alkohol. Aplikasi ini menggunakan model machine learning yang dilatih dengan dataset untuk memberikan prediksi waktu tidur yang optimal.

## Tujuan

- Membantu individu untuk memantau dan mengoptimalkan kualitas tidur mereka berdasarkan faktor kesehatan yang relevan.
- Memberikan rekomendasi tidur berdasarkan data yang dimasukkan oleh pengguna.

## Fitur Utama

- **Prediksi waktu tidur**: Berdasarkan usia, jenis kelamin, penyakit fisik, waktu penggunaan layar, kebiasaan olahraga, dan kebiasaan merokok atau minum alkohol.
- **Model Machine Learning**: Menggunakan **MLPRegressor** yang dilatih untuk memprediksi waktu tidur.
- **Visualisasi Hasil**: Menampilkan perbandingan MAE dan MSE untuk evaluasi model.
- **Halaman interaktif**: Pengguna dapat memasukkan data mereka dan mendapatkan prediksi waktu tidur mereka.

## Teknologi

- **Streamlit**: Untuk membuat aplikasi web interaktif.
- **Pandas**: Untuk pengolahan data.
- **Scikit-learn**: Untuk model machine learning dan preprocessing.
- **Matplotlib**: Untuk visualisasi grafik.

## Cara Menjalankan Aplikasi

### 1. Persiapkan Lingkungan
Pastikan Anda telah menginstall **Python 3** dan **pip** di komputer Anda. Lalu, buatlah virtual environment dan install dependencies berikut:

```bash
pip install -r requirements.txt
