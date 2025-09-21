# 📊 Analisis Missing Data pada Dataset Titanic

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit--Learn](https://img.shields.io/badge/scikit--learn-Imputation-red.svg)
![Affiliation](https://img.shields.io/badge/Affiliation-UNTIRTA-orange.svg)

Repositori ini menyajikan analisis komprehensif terhadap data yang hilang (*missing data*) pada dataset Titanic. Analisis ini mencakup diagnosis mendalam dan demonstrasi tiga metode imputasi yang paling umum dan efektif: **Simple Imputation**, **K-Nearest Neighbors (KNN) Imputation**, dan **Multiple Imputation by Chained Equations (MICE)**. Proyek ini memandu Anda melalui alur kerja lengkap, dari visualisasi pola data yang hilang hingga implementasi dan perbandingan hasil dari setiap metode.

---

## ✨ Fitur Utama

- **🎯 Diagnosis Komprehensif**: Analisis mendalam tentang pola data yang hilang, persentase, dan distribusinya menggunakan tabel ringkasan dan visualisasi khusus dari pustaka `missingno`.
- **🛠️ Implementasi Tiga Metode Imputasi**: Menerapkan tiga strategi imputasi yang berbeda untuk mengatasi masalah data hilang, yaitu:
    1. **Simple Imputation**: Mengisi nilai yang hilang dengan statistik dasar seperti rata-rata, median, atau modus.
    2. **KNN Imputation**: Menggunakan algoritma k-Nearest Neighbors untuk mengisi nilai berdasarkan kemiripan dengan tetangga terdekat.
    3. **MICE Imputation**: Melakukan imputasi iteratif dengan membangun model regresi untuk memprediksi nilai yang hilang, menghasilkan estimasi yang lebih robust.
- **🔄 Otomatisasi & Robustness**: Notebook ini dilengkapi dengan fungsi auto-install dependencies yang cerdas dan penanganan kesalahan yang ditingkatkan untuk memastikan alur kerja yang mulus dan dapat direproduksi.
- **📊 Laporan & Visualisasi Interaktif**: Menyajikan berbagai visualisasi yang jelas, termasuk diagram batang, heatmap, dan boxplot untuk membandingkan distribusi data sebelum dan sesudah imputasi.
- **🔍 Analisis Komparatif Mendalam**: Membandingkan hasil dari setiap metode imputasi melalui tabel ringkasan dan DataFrame perbandingan yang terstruktur, memungkinkan evaluasi langsung terhadap kualitas imputasi.

---

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `Python 3.7+`
- **Pustaka Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `missingno`
- **Lingkungan**: `Jupyter Notebook / Lab`

---

## 🚀 Cara Memulai

### Prasyarat
- **Perangkat Lunak**: Python 3.7+, Jupyter Notebook/Lab.
- **File Data**: Notebook ini menggunakan dataset Titanic yang sudah terintegrasi di dalam pustaka `seaborn`, sehingga tidak memerlukan file data eksternal.

### Instalasi & Penggunaan

1. **Unduh Repositori**: *Clone* atau unduh proyek ini ke komputer Anda.

2. **Jalankan Jupyter Notebook**: Buka terminal atau command prompt, lalu jalankan Jupyter Lab/Notebook dan buka file Python (`.ipynb`).

3. **Instalasi Otomatis**: Skrip dalam notebook dirancang untuk secara otomatis memeriksa dan menginstal pustaka yang dibutuhkan jika belum terpasang.

4. **Jalankan Analisis**: Eksekusi semua sel secara berurutan untuk mereplikasi seluruh alur kerja, dari analisis data hingga perbandingan hasil imputasi.

---

## 📊 Ringkasan Hasil & Perbandingan Metode

Berikut adalah ringkasan hasil dari setiap metode imputasi yang diimplementasikan:

| Metode Imputasi      | Missing Values Sebelum | Missing Values Sesudah | Status           |
|----------------------|------------------------|------------------------|------------------|
| **Simple Imputation**| 866                    | 0                      | ✅ Complete      |
| **KNN Imputation** | 866                    | 0                      | ✅ Complete      |
| **MICE Imputation** | 866                    | 0                      | ✅ Complete      |

**Catatan:** Semua metode berhasil mengisi 100% data yang hilang, namun perbedaan kualitasnya dapat dilihat dari perbandingan distribusi data dan bagaimana setiap metode mempertahankan karakteristik statistik dataset asli.

---

## ⚖️ Lisensi & Ketentuan Penggunaan

- **Hak Cipta**: © 2025 Ferdian Bangkit Wijaya - Seluruh Hak Dilindungi.
- **Penggunaan Akademik**: Diizinkan secara bebas untuk keperluan penelitian dan pendidikan non-komersial dengan atribusi.
- **Penggunaan Komersial**: Memerlukan izin tertulis dari pengembang.

---

## 👨‍💻 Author

- **Ferdian Bangkit Wijaya**
- Universitas Sultan Ageng Tirtayasa (UNTIRTA)
- Banten, Indonesia 🇮🇩

---

> Proyek ini dirancang sebagai panduan praktis untuk mengatasi masalah data hilang, menunjukkan bagaimana pendekatan yang terstruktur dapat menghasilkan dataset yang lebih bersih dan siap untuk analisis lanjutan.
