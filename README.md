MATA KULIAH REALITAS TERKEMBANG 2024/2025 UNIVERSITAS BRAWIJAYA

---

# Aplikasi WebVR 360 Simple: Coffee Shop in Brawijaya

Disusun oleh:  
ASTI SYAFITRI

## Daftar Isi
1. [Penjelasan Singkat Aplikasi](#penjelasan-singkat-aplikasi)  
2. [Teknologi yang Digunakan](#teknologi-yang-digunakan)  
3. [Proses Pembuatan](#proses-pembuatan)
4.  [Referensi](#referensi)  

## Penjelasan Singkat Aplikasi
Aplikasi ini adalah sebuah scene 3D interaktif yang dibuat menggunakan A-Frame, sebuah framework untuk membangun pengalaman Virtual Reality (VR) berbasis web. Aplikasi ini menampilkan beberapa objek 3D (kotak, bola, dan silinder) yang merespons interaksi pengguna seperti gerakan mouse.

## Teknologi yang Digunakan
Aplikasi ini dibangun menggunakan teknologi berikut:
- **HTML**: Untuk struktur dasar halaman web.
- **A-Frame**: Sebuah framework open-source berbasis JavaScript yang digunakan untuk membuat dan mengelola elemen-elemen VR. Disini saya menggunakan versi 0.3 (tidak direkomendasikan karena versi sudah v1.6), namun dikarenakan penggunaannya yang simple melalui tutorial youtube, saya menggunakan versi tersebut.
- **JavaScript**: Digunakan melalui A-Frame untuk mengatur animasi dan interaksi.

- **Komponen A-Frame**:
  - `a-scene`: Menentukan ruang VR.
  - `a-assets`: Menyimpan gambar dan model 3D.
  - `a-sky`: Menampilkan gambar latar 360 derajat.

## Proses Pembuatan
Proses pembuatan aplikasi ini mencakup beberapa langkah:
1. Inisialisasi Scene: Menggunakan tag <a-scene> untuk mendefinisikan area VR.
2. Penambahan Aset: Menggunakan tag <a-assets> untuk mendefinisikan aset seperti tekstur gambar.
3. Penambahan Objek 3D:
  - Kotak: Menggunakan <a-box> dengan animasi rotasi yang dimulai saat mouse masuk ke area kotak.
  - Bola: Menggunakan <a-sphere> dengan animasi perubahan skala dan warna saat mouse masuk dan keluar dari area bola.
  - Silinder: Menggunakan <a-cylinder> dengan animasi perubahan posisi saat mouse masuk dan keluar dari area silinder.
4. Kamera dan Kursor: Menggunakan <a-camera> dan <a-cursor> untuk mengatur perspektif pengguna dan interaksi kursor.



## Referensi
- [A-Frame WebVR Tutorial 6 - Interacting With Objects](https://www.youtube.com/watch?v=yM89f0GLzB0&t=228s) oleh Sonar System.

---
