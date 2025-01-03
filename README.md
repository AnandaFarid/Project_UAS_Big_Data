# **<center>Final Project UAS Big Data</center>**


![LOGO](blog-7-strategi-meningkatkan-review-positif-dari-tamu-hotel-67-l.jpg)

# <center>Eksplorasi Analisis Hotel </center>

## **Table of Contents**

1. [🏷️ **Title**](#Title)
2. [🌟 **Overview**](#Overview)
3. [🎯 **Objective**](#Objective)
4. [📊 **Dataset**](#Dataset)
5. [🔍 **Methodology**](#Methodology)
6. [💡 **Insights**](#Insights)
7. [⚙️ **Dependencies**](#Dependencies)
8. [🚀 **Usage**](#Usage)
9. [👥 **Team Members**](#Team-Members)
10. [📂 **Repository Structure**](#Repository-Structure)
11. [📚 **References**](#References)


[🌟 **Overview**](#Overview)

Proyek ini bertujuan untuk mengeksplorasi dan menganalisis data lagu-lagu Spotify dengan fokus pada genre, fitur audio, dan tren yang muncul. Melalui eksplorasi data (EDA), analisis ini bertujuan untuk mengidentifikasi pola-pola musik yang relevan dan memberikan wawasan tentang hubungan antar genre dan fitur yang mempengaruhi popularitas lagu. Sebagai tambahan, K-Nearest Neighbors (KNN) digunakan untuk memberikan rekomendasi berdasarkan pola-pola musik yang terdeteksi, meskipun fokus utama dari proyek ini adalah analisis eksplorasi data dan pemahaman karakteristik musik seperti danceability, energy, dan acousticness.

---

[🎯 **Objective**](#Objective)

Tujuan dari proyek ini adalah untuk mengungkap tren dan pola utama dalam perilaku pelanggan, mengidentifikasi faktor-faktor yang memengaruhi pembatalan, dan memberikan wawasan berdasarkan data untuk mengoptimalkan operasi hotel.

---

[📊 **Dataset**](#Dataset)

Dataset berasal dari proyek [TidyTuesday](https://github.com/rfordatascience/tidytuesday) dan dikumpulkan menggunakan paket [`hotels`](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-02-11/hotels.csv). Data dirilis pada **21 Januari 2020** dan dapat diakses melalui tautan berikut:  
[hotels.csv](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-02-11/hotels.csv).

Paket `hotels` digunakan untuk mendapatkan hotel, is_canceled, customer_type, reservation_status, market_segment.

### Variabel dalam Dataset:
Dataset ini terdiri dari 32 variabel, termasuk:
- `hotel`: Jenis hotel (City Hotel atau Resort Hotel).
- `is_canceled`: Status pemesanan (0 = Tidak, 1 = Ya).
- `lead_time`: Jumlah hari antara pemesanan dan tanggal kedatangan.
- `arrival_date_year`,: Tahun Kedatangan

---

## **Methodology**

1. Data import and cleaning.
2. Exploratory Data Analysis (EDA).

[💡 **Insights**](#Insights)

[Summarize the key findings from your analysis, highlighting important patterns or trends.]

---

[⚙️ **Dependencies**](#Dependencies)

Proyek ini menggunakan beberapa dependensi untuk menjalankan analisis. Berikut adalah daftar dependensi yang diperlukan:

pandas, versi 1.4.3
openpyxl, versi 3.0.10
numpy, versi 1.23.0
numpy-stl, versi 2.17.1
matplotlib, versi 3.5.2
ipympl, versi 0.9.1
jupyterlab, versi 3.4.4
ipywidgets, versi 7.7.1
tqdm, versi 4.64.0
Catatan: Belum diuji sepenuhnya, namun bisa digunakan di lingkungan Python.
