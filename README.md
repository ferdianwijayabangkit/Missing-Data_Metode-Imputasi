# 📊 Analisis Missing Data pada Dataset Titanic

![R](https://img.shields.io/badge/R-4.0+-blue.svg)
![RStudio](https://img.shields.io/badge/RStudio-RMarkdown-purple.svg)
![mice](https://img.shields.io/badge/MICE-Imputation-green.svg)
![Affiliation](https://img.shields.io/badge/Affiliation-UNTIRTA-orange.svg)

Repositori ini menyajikan analisis komprehensif terhadap data yang hilang (*missing data*) pada dataset Titanic. Proyek ini mendemonstrasikan alur kerja lengkap di **R**, dari diagnosis pola data yang hilang hingga implementasi dan perbandingan tiga metode imputasi yang efektif: **Simple Imputation**, **K-Nearest Neighbors (KNN) Imputation**, dan **Multiple Imputation by Chained Equations (MICE)**.

---

## ✨ Fitur Utama

- **🎯 Diagnosis Komprehensif**: Menganalisis pola data yang hilang, persentase, dan distribusinya secara mendalam menggunakan visualisasi dari pustaka `VIM` dan `visdat`.
- **🛠️ Implementasi Tiga Metode Imputasi**: Menerapkan tiga strategi imputasi yang berbeda secara efektif untuk menangani data yang hilang.
    - **Simple Imputation**: Mengisi nilai yang hilang dengan statistik dasar seperti **rata-rata**, **median**, atau **modus**.
    - **KNN Imputation**: Menggunakan algoritma **K-Nearest Neighbors** untuk mengisi nilai berdasarkan kemiripan dengan tetangga terdekat, mempertahankan struktur data.
    - **MICE Imputation**: Melakukan **imputasi iteratif** dengan membangun model regresi untuk memprediksi nilai yang hilang, menghasilkan estimasi yang lebih kuat dan andal.
- **⚙️ Otomatisasi & Robustness**: Dilengkapi dengan skrip R yang **otomatis memeriksa dan menginstal pustaka** yang dibutuhkan, memastikan alur kerja dapat berjalan dengan lancar tanpa hambatan teknis.
- **📊 Laporan Reproducible**: Menyajikan file R Markdown (`.Rmd`) yang **menghasilkan laporan analisis lengkap** yang dapat dibagikan dan direproduksi dengan mudah.
- **🔍 Analisis Komparatif Mendalam**: Menyediakan perbandingan hasil dari setiap metode imputasi melalui **DataFrame perbandingan yang terstruktur**, memungkinkan evaluasi langsung dan jelas terhadap kualitas imputasi.

---

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `R 4.0+`
- **Pustaka R**: `dplyr`, `tidyr`, `ggplot2`, `VIM`, `mice`, `knitr`, `DT`, dan lainnya.
- **Lingkungan**: `RStudio` / `R Markdown`

---

## 🚀 Cara Memulai

### Prasyarat
- **Perangkat Lunak**: R 4.0+ dan RStudio.

### Instalasi & Penggunaan

1. **Unduh Repositori**: *Clone* atau unduh proyek ini ke komputer Anda.

2. **Jalankan RStudio**: Buka RStudio dan buka file `Analisis_Missing_Data.Rmd`.

3. **Instalasi Otomatis**: Skrip dalam R Markdown akan secara otomatis memeriksa dan menginstal semua paket yang diperlukan saat Anda mengeksekusi *chunk* pertama.

4. **Jalankan Analisis**: Tekan tombol **"Knit"** untuk menjalankan seluruh alur kerja dan menghasilkan laporan dalam format HTML atau PDF, atau jalankan setiap *chunk* kode secara berurutan.

---

## 📊 Ringkasan Hasil & Perbandingan Metode

Berikut adalah ringkasan hasil dari setiap metode imputasi yang diimplementasikan:

| Metode Imputasi      | Missing Values Sebelum | Missing Values Sesudah | Status           |
|----------------------|------------------------|------------------------|------------------|
| **Simple Imputation**| 866                    | 0                      | ✅ Complete      |
| **KNN Imputation** | 866                    | 0                      | ✅ Complete      |
| **MICE Imputation** | 866                    | 0                      | ✅ Complete      |

**Catatan**: Semua metode berhasil mengisi 100% data yang hilang, menunjukkan keberhasilan implementasi.

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

> R Markdown ini menggunakan dataset Titanic built-in R yang telah dimodifikasi untuk menciptakan missing values yang realistis untuk keperluan demonstrasi metode imputasi.
