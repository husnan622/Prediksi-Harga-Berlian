# Prediksi Harga Berlian - Husnan

## Domain Proyek

Bayangkan Anda adalah pemilik perusahaan yang bergerak di bidang jual-beli berlian. Model bisnis Anda adalah distributor dan retail, perusahaan membeli diamonds dari produsen kemudian menjualnya kepada konsumen. Perusahaan juga menerima penjualan kembali diamonds dari konsumen. Untuk efisiensi, Anda ingin menerapkan automasi pada sistem dalam memprediksi harga diamonds dengan teknik predictive modelling.

## Business Understanding

### Problem Statements
- Dari serangkaian fitur yang ada, fitur apa yang paling berpengaruh terhadap harga diamonds?
- Berapa harga pasar diamonds dengan karakteristik atau fitur tertentu?  

### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Mengetahui fitur yang paling berkorelasi dengan harga diamonds.
- Membuat model machine learning yang dapat memprediksi harga diamonds seakurat mungkin berdasarkan fitur-fitur yang ada.

## Data Understanding

Data yang digunakan pada proyek kali ini adalah Diamond dataset yang diunduh dari [repository GitHub ggplot](https://github.com/tidyverse/ggplot2/tree/main/data-raw). Dataset ini memiliki 53.940 jenis diamonds dengan berbagai karakteristik dan harga. Karakteristik yang dimaksud di sini adalah fitur non-numerik seperti cut, color, dan clarity, serta fitur numerik seperti carat, x, y, z, table, dan depth. Kesembilan fitur ini adalah fitur yang akan digunakan dalam menemukan pola pada data, sedangkan harga merupakan fitur target.

## Data Preparation
Pada bagian ini kita akan melakukan empat tahap persiapan data, yaitu:
- Encoding fitur kategori.
- Reduksi dimensi dengan Principal Component Analysis (PCA).
- Pembagian dataset dengan fungsi train_test_split dari library sklearn.
- Standarisasi.

## Modeling
Pada tahap ini, kita akan mengembangkan model machine learning dengan tiga algoritma. Kemudian, kita akan mengevaluasi performa masing-masing algoritma dan menentukan algoritma mana yang memberikan hasil prediksi terbaik. Ketiga algoritma yang akan kita gunakan, antara lain:
- K-Nearest Neighbor
- Random Forest
- Boosting Algorithm

## Evaluation
Metrik yang akan kita gunakan pada prediksi ini adalah MSE atau Mean Squared Error yang menghitung jumlah selisih kuadrat rata-rata nilai sebenarnya dengan nilai prediksi. Hasil evaluasi pada data latih dan data test adalah model Random Forest (RF) memberikan nilai eror yang paling kecil. Sedangkan model dengan algoritma Boosting memiliki eror yang paling besar. Model inilah yang akan kita pilih sebagai model terbaik untuk melakukan prediksi harga diamonds.
