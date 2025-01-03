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

## **Dataset**

Dataset berasal dari proyek [TidyTuesday](https://github.com/rfordatascience/tidytuesday) dan dikumpulkan menggunakan paket [`hotels`](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-02-11/hotels.csv). Data dirilis pada **21 Januari 2020** dan dapat diakses melalui tautan berikut:  
[hotels.csv](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-02-11/hotels.csv).

Paket `spotifyr` digunakan untuk mendapatkan metadata lagu dari API Spotify, mencakup informasi seperti popularitas lagu, nama artis, album, genre, serta atribut audio (danceability, energy, valence, dll.).

### Variabel dalam Dataset:
Dataset ini terdiri dari 19 variabel, termasuk:
- `track_id`, `track_name`, `track_artist`: Identifikasi dan informasi dasar mengenai lagu.
- `track_popularity`: Popularitas lagu berdasarkan nilai antara 0-100.
- `playlist_name`, `playlist_genre`: Nama playlist dan genre playlist terkait.
- `danceability`, `energy`, `acousticness`, dan lainnya: Atribut audio yang menggambarkan karakteristik musik lagu seperti keterpaduan untuk berdansa, energi, keaslian suara, dan lainnya.

---

## **Methodology**

1. Data import and cleaning.
2. Exploratory Data Analysis (EDA).
3. Optional: Advanced analysis KNN untuk song recommendation system
