# Lab9web


TUGAS PERTEMUAN 11

PEMROGRAMAN WEB

TEKNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA

NAMA : Arip Hidayattuloh

NIM : 312010244

KELAS : TI.20.B1

DOSEN : Agung Nugroho,S.Kom.,M.Kom

Pemrograman Web: PHP Modular

### Instruksi Praktikum

1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

### Menjalankan MySQL Server

Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![Gambar1](screenshot/ss1.png)

Gambar 01. XAMPP Control

Buat folder lab9_php_modular pada root directory web server (C:\xampp\htdocs)

![Gambar1](screenshot/ss2.png)

Langkah-langkah Praktikum
Buat file baru dengan nama header.php4.

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
</head>
<body>
<div class="container">
<header>
<h1>Modularisasi Menggunakan Require</h1>
</header>
<nav>
<a href="home.php">Home</a>
<a href="about.php">Tentang</a>
<a href="kontak.php">Kontak</a>
</nav>
```

![Gambar1](screenshot/ss3.png)

Buat file baru dengan nama footer.php

```
<footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
```

![Gambar1](screenshot/ss4.png)

Buat file baru dengan nama home.php

```
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

![Gambar1](screenshot/ss5.png)


Buat file baru dengan nama about.php
```
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman About</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```


![Gambar1](screenshot/ss6.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/lab9_php_modular/

![Gambar1](screenshot/ss7.png)

Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template

Jawab:

Buat folder Tugas lab9_php_modular pada root directory web server (C:\xampp\htdocs\lab9_php_modular\Lab9_Tugas Modularisasi)



