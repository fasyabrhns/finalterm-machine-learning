# 🤖 Final Term Machine Learning Project

Repository ini merupakan submisi untuk **Ujian Akhir Semester (UAS)** mata kuliah Machine Learning. Proyek ini mencakup tiga domain utama pembelajaran mesin: Analisis Regresi, Analisis Data Transaksi, dan Klasifikasi Gambar (Computer Vision).

## 👨‍🎓 Profil Mahasiswa

| Atribut | Detail |
| :--- | :--- |
| **Nama** | **Fasya Burhanis Syauqi** |
| **NIM** | **1103223054** |
| **Mata Kuliah** | Machine Learning |

---

## 📂 Project Overview

Repository ini terdiri dari tiga bagian utama (end-to-end projects) yang masing-masing berfokus pada teknik *machine learning* yang berbeda:

### 1. 📈 Regression Analysis
Berfokus pada pemodelan prediktif menggunakan teknik regresi.
- **Lokasi:** Folder `/Regression`
- **Tujuan:** Memprediksi nilai kontinu berdasarkan variabel independen yang tersedia dalam dataset.

### 2. 🛒 Transaction Data Analysis
Berfokus pada analisis pola pembelian atau data transaksi.
- **Lokasi:** Folder `/Transaction`
- **Tujuan:** Menganalisis data transaksi untuk menemukan pola (seperti *Market Basket Analysis* atau *Clustering* pelanggan).

### 3. 🖼️ Image Classification & Computer Vision
Penerapan Deep Learning untuk klasifikasi gambar.
- **Notebook Utama:** `Image_Classification_Cat_Breeds.ipynb`
- **Dataset Tambahan:** `FishImgDataset`
- **Model Deployment:** Tersedia model yang sudah dikonversi ke format TFLite (`MobileNet.tflite`, `mobilenet_v2.tflite`) untuk kebutuhan deployment pada perangkat mobile/IoT.
- **Arsitektur:** Menggunakan **MobileNet** sebagai *base model* (Transfer Learning) untuk efisiensi komputasi.

---

## 🛠️ Repository Structure

Berikut adalah struktur file dalam repository ini:

```text
finalterm-machine-learning/
├── 📂 FishImgDataset/                 # Dataset gambar ikan
├── 📂 Regression/                     # Project regresi (kode & data)
├── 📂 Transaction/                    # Project analisis transaksi (kode & data)
├── 📄 Image_Classification_Cat_Breeds.ipynb  # Notebook klasifikasi ras kucing
├── 📄 MobileNet.tflite                # Model TFLite V1
├── 📄 mobilenet_v2.tflite             # Model TFLite V2
└── 📝 README.md                       # Dokumentasi proyek
