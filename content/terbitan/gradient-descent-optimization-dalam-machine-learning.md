---
layout: post
title: GRADIENT DESCENT OPTIMIZATION DALAM MACHINE LEARNING
date: 2024-02-18T10:15:30.824Z
---
![](/images/uploads/gradient-isbn.jpg)

**P﻿enulis:** Prof. Kuntoro, dr., MPH, DR,PH. \
\
**H﻿arga:** Rp. 75.000\
\
Optimasi pada Neural Network merupakan algoritma yang dapat mencari nilai optimal, baik itu dengan meminimalkan ataupun memaksimalkan fungsi objektif (fungsi kesalahan). Sederhananya, output dari semua proses perhitungan dalam Neural Network dipelajari dan diperbarui kearah solusi yang optimal, yaitu dengan meminimalkan kerugian dengan proses Training.Pada umumnya, optimasi dibagi menjadi 2 kategori yaitu algoritma optimasi orde pertama yaitu menggunakan nilai Gradient dan algoritma optimasi orde selanjutnya yang menggunakan Hessian.Perbandingan dari kedua jenis tersebut adalah pada teknik optimasi orde pertama mudah untuk dihitung, lebih sedikit memakan waktu dan cukup cepat dalam memproses dataset yang besar. Sedangkan pada teknik optimasi orde kedua lebih cepat hanya jika derifativ parsial kedua diketahui, namun teknik ini selalu lebih lambat dan mahal untuk diproses dalam hal waktu dan memori. 

Gradient merupakan nilai kemiringan atau kecondongan suatu garis yang membandingkan antara komponen y (ordinat) dengan komponen x (absis). Gradient disini merupakan nilai kemiringan suatu fungsi, yaitu tingkat perubahan parameter terhadap jumlah parameter lain. Secara matematis, gradient dapat digambarkan sebagai turunan parsial dari serangkaian parameter terhadap inputnya. Semakin banyak gradient maka semakin curam lerengnya.Gradient Descent juga digambarkan sebagai iterasi yang digunakan untuk menemukan nilai optimal dari parameter dengan menggunakan kalkulus untuk menemukan nilai minimum. Gradient Descent digunakan untuk pembaruan bobot dalam Neural Network dengan cara meminimalkan loss function. Proses Gradient Descent ini terjadi pada fase backpropagation.