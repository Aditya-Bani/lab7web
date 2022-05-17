| Nama      | Fajar Agung Nugroho |
| ----------- | ----------- |
| NIM     | 312010448       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 7

## 1. Install XAMPP
Install XAMPP dari https://www.apachefriends.org/download.html

![img1!](assets/img/1.PNG)

## 2. Menjalankan web server
Untuk menjalankan web server dari menu XAMPP Control

![img1!](assets/img/2.PNG)
Menjalankan XAMPP dengan cara klik tombol Start pada server Apache seperti gambar diatas

## 3. Memulai PHP
Buat folder lab7_php_dasar pada root directory web server (\xampp\htdocs)

![img2!](assets/img/3.PNG)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab7_php_dasar/

## 4. PHP Dasar
Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat
kode seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
    echo "Hello World";
    ?>
    </body>
    </html>
```

Berikut hasil run PHP Dasar
![img2!](assets/img/4.PNG)



### Variable PHP
Menambahkan variable pada program.

![img2!](assets/img/4/3.png)

![img2!](assets/img/4/4.png)

### Predefine Variable `$_GET`
![img2!](assets/img/4/5.png)

Untuk mengaksesnya gunakan URL:
http://localhost/lab7_php_dasar/php_dasar.php?nama=Fajar

![img2!](assets/img/4/6.png)

## 5. Membuat Form Input
![img2!](assets/img/5/11.png)

![img2!](assets/img/5/12.png)

### Operator
![img2!](assets/img/5/13.png)

### Kondisi IF
![img2!](assets/img/5/14.png)

### Kondisi Switch
![img2!](assets/img/5/15.png)

### Perulangan for
![img2!](assets/img/5/16.png)

### Perulangan while
![img2!](assets/img/5/17.png)

### Perulangan do while
![img2!](assets/img/5/18.png)

## Pertanyaan dan Tugas
Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan
nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung
umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang
berbeda-beda sesuai pilihan pekerjaan.

## Jawab
### Pertama saya akan membuat 1 module dan 3 package

![img2!](assets/img/praktikum/1.png)

terdapat folder core yang berisi file umur.php dan gaji.php

dimana file `umur.php` untuk menampilkan output dengan menghitung
umur berdasarkan inputan tanggal lahir, 

Lalu file `gaji.php` untuk menentukan gaji yang berbeda-beda sesuai pilihan pekerjaan,

dan file `index.php` sebagai halaman utama dalam program sederhana ini.

### Menentukan umur berdasarkan tanggal lahir
![img2!](assets/img/praktikum/umur.png)

Untuk menentukan umur berdasarkan tgl lahir, saya menggunakan ``date_diff()`` yang berfungsi untuk menghitung selisih waktu dengan format penulisan seperti diatas

### Menentukan gaji sesuai dengan pilihan pekerjaan
![img2!](assets/img/praktikum/gaji.png)

Untuk Menentukan gaji sesuai dengan pilihan pekerjaan, saya menggunakan pengkondisian ``if()`` dan untuk opsi pilihan html menggunakan type `select`. dimana jika saya memilih dokter maka gaji saya adalah 10jt /bulan, jika tidak maka saya akan memilih pilihan selanjutnya. dst sampai tidak ada pilihan yang tersisa

### Form Input
![img2!](assets/img/praktikum/form.png)

Untuk form saya menggunakan method `POST`, dan action ``$_SERVER["PHP_SELF"]`` yaitu variabel super global yang mengembalikan nama file dari skript yang sedang dieksekusi. Jadi ``$_SERVER["PHP_SELF"]`` mengirimkan data formulir yang dikirimkan ke halaman itu sendiri

### Form Output
![img2!](assets/img/praktikum/output.png)

didalam kolom tabel saya menyisipkan sintaks php ke dalam html supaya pas nanti di run akan muncul output yg sebelumnya sudah di input

untuk kolom umur dan gaji saya memanggil file php terpisah, tujuan nya agar penulisan kode terlihat lebih rapi

## Output
![img2!](assets/img/praktikum/11.png)

![img2!](assets/img/praktikum/12.png)

![img2!](assets/img/praktikum/13.png)


