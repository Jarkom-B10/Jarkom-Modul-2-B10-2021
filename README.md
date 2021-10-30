# Jarkom-Modul-2-B10-2021

## Anggota B10
Nama | NRP
------------ | -------------
Pramudya Tiandana Wisnu Gautama | 05111940000018
Jason Andrew Gunawan | 05111940000085
Frans Wijaya | 05111940000098

### ps:
- yyy pada url adalah kode kelompok anda
- File Requirement [Github](https://github.com/FeinardSlim/Praktikum-Modul-2-Jarkom)

## Soal 1
Luffy adalah seorang yang akan jadi Raja Bajak Laut. Demi membuat Luffy menjadi Raja Bajak Laut, Nami ingin membuat sebuah peta, bantu Nami untuk membuat peta berikut:
![topologi](/img/topologi.png)
EniesLobby akan dijadikan sebagai DNS Master, Water7 akan dijadikan DNS Slave, dan Skypie akan digunakan sebagai Web Server. Terdapat 2 Client yaitu Loguetown, dan Alabasta. Semua node terhubung pada router Foosha, sehingga dapat mengakses internet (1).
### Solusi 1

## Soal 2
Luffy ingin menghubungi Franky yang berada di EniesLobby dengan denden mushi. Kalian diminta Luffy untuk membuat website utama dengan mengakses **franky.yyy.com** dengan alias **www.franky.yyy.com** pada folder kaizoku (2).
### Solusi 2

## Soal 3
Setelah itu buat subdomain **super.franky.yyy.com** dengan alias **www.super.franky.yyy.com** yang diatur DNS nya di EniesLobby dan mengarah ke Skypie(3).
### Solusi 3

## Soal 4
Buat juga reverse domain untuk domain utama (4). 
### Solusi 4

## Soal 5
Supaya tetap bisa menghubungi Franky jika server EniesLobby rusak, maka buat Water7 sebagai DNS Slave untuk domain utama (5).
### Solusi 5

## Soal 6
Setelah itu terdapat subdomain **mecha.franky.yyy.com** dengan alias **www.mecha.franky.yyy.com** yang didelegasikan dari EniesLobby ke Water7 dengan IP menuju ke Skypie dalam folder sunnygo(6).
### Solusi 6

## Soal 7
Untuk memperlancar komunikasi Luffy dan rekannya, dibuatkan subdomain melalui Water7 dengan nama **general.mecha.franky.yyy.com** dengan alias **www.general.mecha.franky.yyy.com** yang mengarah ke Skypie(7).
### Solusi 7

## Soal 8
(8) Setelah melakukan konfigurasi server, maka dilakukan konfigurasi Webserver. Pertama dengan webserver **www.franky.yyy.com**. Pertama, luffy membutuhkan webserver dengan DocumentRoot pada /var/www/franky.yyy.com.
### Solusi 8

## Soal 9
(9) Setelah itu, Luffy juga membutuhkan agar url **www.franky.yyy.com/index.php/home** dapat menjadi menjadi **www.franky.yyy.com/home**.
### Solusi 9

## Soal 10
(10) Setelah itu, pada subdomain **www.super.franky.yyy.com**, Luffy membutuhkan penyimpanan aset yang memiliki DocumentRoot pada /var/www/super.franky.yyy.com.
### Solusi 10

## Soal 11
(11) Akan tetapi, pada folder /public, Luffy ingin hanya dapat melakukan directory listing saja.
### Solusi 11

## Soal 12
(12) Tidak hanya itu, Luffy juga menyiapkan error file 404.html pada folder /error untuk mengganti error kode pada apache.
### Solusi 12

## Soal 13
(13) Luffy juga meminta Nami untuk dibuatkan konfigurasi virtual host. Virtual host ini bertujuan untuk dapat mengakses file asset **www.super.franky.yyy.com/public/js** menjadi **www.super.franky.yyy.com/js**.
### Solusi 13

## Soal 14
(14) Dan Luffy meminta untuk web **www.general.mecha.franky.yyy.com** hanya bisa diakses dengan port 15000 dan port 15500.
### Solusi 14

## Soal 15
dengan autentikasi username luffy dan password onepiece dan file di /var/www/general.mecha.franky.yyy.
### Solusi 15

## Soal 16
Dan setiap kali mengakses IP **Skypie** akan dialihkan secara otomatis ke **www.franky.yyy.com**.
### Solusi 16

## Soal 17
Dikarenakan Franky juga ingin mengajak temannya untuk dapat menghubunginya melalui website **www.super.franky.yyy.com**, dan dikarenakan pengunjung web server pasti akan bingung dengan randomnya images yang ada, maka Franky juga meminta untuk mengganti request gambar yang memiliki substring “franky” akan diarahkan menuju *franky.png*.
### Solusi 17


## Kendala
- Terjadi masalah ketika aplikasi GNS3 crash, yang menyebabkan semua data yang belum di-backup hilang (nomor 8-16). Sehingga kami harus mengerjakan ulang yang tentu saja memakan waktu lebih.