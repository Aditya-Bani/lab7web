| Nama      | Aditya Bani Isro |
| ----------- | ----------- |
| NIM     | 312010134       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 7

## 1. Install XAMPP
Install XAMPP dari https://www.apachefriends.org/download.html

![img1!](assets/img/1.PNG)

## 2. Menjalankan web server
Untuk menjalankan web server dari menu XAMPP Control

![img2!](assets/img/2.PNG)
Menjalankan XAMPP dengan cara klik tombol Start pada server Apache seperti gambar diatas

## 3. Memulai PHP
Buat folder lab7_php_dasar pada root directory web server (\xampp\htdocs)

![img3!](assets/img/3.PNG)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab7_php_dasar/

![img4](assets/img/4.PNG)

## 4. PHP Dasar
Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat
kode seperti berikut.

![img5](assets/img/5.PNG)

Berikut hasil run PHP Dasar
![img6!](assets/img/6.PNG)

### Variable PHP
Menambahkan variable pada program.

![img7!](assets/img/7.PNG)

![img8!](assets/img/8.PNG)

### Predefine Variable `$_GET`
![img9!](assets/img/9.PNG)

Untuk mengaksesnya gunakan URL:
http://localhost/lab7_php_dasar/php_dasar.php?nama=%20AdityaBani

![img10!](assets/img/10.PNG)

## 5. Membuat Form Input
![img11!](assets/img/11.PNG)

![img12!](assets/img/12.PNG)

### Operator
![img13!](assets/img/13.PNG)

![img14!](assets/img/14.PNG)

### Kondisi IF
![img15!](assets/img/15.PNG)

![img16!](assets/img/16.PNG)

### Kondisi Switch
![img17!](assets/img/17.PNG)

![img18](assets/img/18.PNG)

### Perulangan for
![img19!](assets/img/19.PNG)

![img20!](assets/img/20.PNG)

### Perulangan while
![img21!](assets/img/21.PNG)

![img22](assets/img/22.PNG)

### Perulangan do while
![img23!](assets/img/23.PNG)

![img24!](assets/img/24.PNG)

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


