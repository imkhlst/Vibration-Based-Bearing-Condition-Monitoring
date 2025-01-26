# Thesis Project for Bachelor Degree

## Project Overview
Dalam perkembangan teknologi dalam sektor industri yang sangat cepat, sangat memungkinkan mengumpulkan data sensor dalam jumlah besar dari berbagai mesin. Dalam kasus tertentu, mesin diaplikasikan dalam kondisi yang tidak menguntungkan seperti masalah pelumasan, misalignment dan overload yang dapat menyebabkan kerusakan pada mesin yang membutuhkan maintenance dengan biaya tinggi dan waktu yang cukup lama. Beberapa survey yang dilakukan oleh IEEE Industry Application Society (IEEE-IAS) dan Japan Electrical Manufacturers’ Association (JEMA) mengungkapkan bahwa kerusakan bearing merupakan kerusakan yang umum terjadi dan lebih dari 40% menjadi penyebab kerusakan mesin [[1](https://www.mdpi.com/472794)].

Predictive based maintenance adalah salah satu metode perawatan pada kondisi mesin yang terdiri dari pemantauan secara periodik, mengidentifikasi komponen mesin yang bermasalah dan melakukan perencanaan perawatan [[2](http://ejurnal.its.ac.id/index.php/teknik/article/view/27527)}. Machine Learning merupakan cabang keilmuan penting *Artificial Intellignece* yang membantu menganalisa data berdasarkan model yang dilatih dan secara akurat dapat memprediksi fenomena berdasarkan pola tertentu. *Convolutional Neural Network* (CNN) merupakan algoritma yang popular digunakan dengan keakuratannya yang tinggi dalam mengenali gambar diantara algoritma yang lain. *Spectrogram* merupakan grafik ilustrasi dari variasi frekuensi terhadap waktu atau gambaran sederhana mengenai getaran pada waktu tertentu yang tampil dalam warna yang berbeda sesuai dengan kekuatan sinyal getaran/suara. Spectrogram dihasilkan dengan menggunakan metode *Short Time Fourier Transform* (STFT) dengan membagi sinyal menjadi beberapa bagian dalam domain waktu dengan pemilihan jendela fungsi yang tepat kemudian melakukan *Fourier Transform* pada masing-masing bagian secara terpisah dan memberikan spektrum seketika untuk memberikan visualisasi sinyal. Proyek ini bertujuan untuk mendeteksi kerusakan pada bantalan menggunakan sistem motor poros sederhana menerapkan metode CNN *Machine learning* dengan mengubah data getaran menjadi *spectrogram*.

## Problem Statement
Berikut ini beberapa masalah yang harus diselesaikan.
1. Bagaimana cara mengolah data getaran agar bisa visualisasikan dan diubah menjadi citra spectrogram?
2. Bagaimana membuat model yang dapat mendeteksi kerusakan pada bantalan?

## Goals
Berikut tujuan dari proyek ini.
1. Mengetahui cara mengolah data agar dapat digunakan dan diubah menjadi citra spectrogram.
2. Mendapatkan model dan hasil prediksi kerusakan pada bantalan.

## Rerefemce
[1] M. Kahr, G. Kovács, M. Loinig, dan H. Brückl, “Condition Monitoring of Ball Bearings Based on Machine Learning with Synthetically Generated Data,” Sensors, vol. 22, no. 7, hal. 2490, Mar 2022, doi: 10.3390/s22072490.

[2] F. R. Adi, “Identifikasi Keausan Bantalan Tirus (Tapered Bearing) Berbasis Analisis Vibrasi dengan Metode Support Vector Machine (SVM),” Institut Teknologi Bandung, 2017.
