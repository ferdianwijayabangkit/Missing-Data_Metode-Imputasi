# 📊 Analisis Missing Data pada Dataset Titanic
### **Implementasi Tiga Metode Imputasi dalam Python dan R**

Repositori ini menyajikan alur kerja komprehensif untuk menganalisis dan mengatasi masalah **missing data** pada dataset Titanic. Proyek ini mendemonstrasikan implementasi paralel di **Python** dan **R** untuk tiga metode imputasi yang berbeda: **Simple Imputation**, **K-Nearest Neighbors (KNN) Imputation**, dan **Multiple Imputation by Chained Equations (MICE)**.

---

## ✨ Fitur Utama

- **Analisis Dwi-Bahasa**: Menampilkan implementasi yang sama (imputasi data) dalam dua bahasa pemrograman utama yang berbeda, yaitu Python dan R.
- **Diagnosis Komprehensif**: Menganalisis pola data yang hilang, persentase, dan distribusinya menggunakan pustaka `missingno` (Python) dan `VIM` (R).
- **Implementasi Tiga Metode Imputasi**: Menerapkan tiga strategi imputasi yang berbeda:
    - **Simple Imputation**: Mengisi nilai yang hilang dengan statistik dasar seperti rata-rata atau modus.
    - **KNN Imputation**: Menggunakan algoritma k-Nearest Neighbors untuk mengisi nilai berdasarkan kemiripan.
    - **MICE Imputation**: Melakukan imputasi iteratif yang menghasilkan estimasi yang lebih robust.
- **Otomasi & Robustness**: Notebook dan R Markdown dilengkapi dengan fungsi auto-install dependencies yang cerdas dan penanganan kesalahan yang ditingkatkan untuk memastikan alur kerja yang mulus.
- **Laporan yang Dapat Direproduksi**: Menyediakan file Jupyter Notebook (`.ipynb`) dan R Markdown (`.Rmd`) yang menghasilkan laporan analisis lengkap, dari pemuatan data hingga perbandingan hasil.

---

## 📂 Struktur Proyek

- `Missing Data.ipynb`: Notebook Python untuk analisis missing data pada dataset Titanic.
- `Missing Data.Rmd`: Dokumen R Markdown untuk analisis missing data pada dataset Titanic.

*(Catatan: Proyek ini menggunakan dataset Titanic yang sudah tersedia di pustaka Python (`seaborn`) dan R, sehingga tidak memerlukan file data eksternal.)*

---

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `Python 3.7+`, `R 4.0+`
- **Pustaka Python**: `pandas`, `numpy`, `seaborn`, `scikit-learn`, `missingno`.
- **Pustaka R**: `dplyr`, `tidyr`, `ggplot2`, `VIM`, `mice`, `knitr`, `rmarkdown`, `DT`.
- **Lingkungan**: `Jupyter Notebook / Lab`, `RStudio`.

---

## 🚀 Cara Memulai

### Prasyarat

- Instalasi Python dan R.
- Pustaka yang diperlukan (akan diinstal secara otomatis oleh skrip).
- Jupyter Notebook/Lab atau RStudio.

### Instalasi & Penggunaan

1. **Unduh Repositori**: *Clone* atau unduh proyek ini ke komputer Anda.
2. **Jalankan Notebook/R Markdown**:
    - Untuk proyek Python, jalankan Jupyter Lab/Notebook dan buka file Missing Data.ipynb.
    - Untuk proyek R, buka RStudio dan buka file Missing Data.Rmd lalu klik "Knit" atau jalankan chunk kode.
3. **Pustaka Otomatis**: Semua skrip telah dirancang untuk secara otomatis menginstal pustaka yang diperlukan jika belum terpasang.

---

## 📊 Ringkasan Hasil Utama

| Proyek | Masalah | Metode Utama | Hasil Utama |
|---|---|---|---|
| Missing Data Titanic | Missing Values | Simple, KNN, MICE Imputation | Semua metode berhasil mengisi 100% data yang hilang, dengan MICE memberikan hasil paling robust. |

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

Repositori ini berfungsi sebagai panduan praktis untuk mengatasi masalah missing data, menunjukkan bagaimana pendekatan terstruktur dan penggunaan bahasa pemrograman yang fleksibel dapat menghasilkan dataset yang bersih dan siap untuk analisis lanjutan.
