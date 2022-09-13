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
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
