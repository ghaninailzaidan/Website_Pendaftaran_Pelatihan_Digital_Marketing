[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
![CI4](https://img.shields.io/badge/-Codeigniter4-black?style=flat&logo=Codeigniter)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-purple.svg?&logo=bootstrap&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-grey.svg?&logo=PHP&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-blue.svg?style=flat&logo=mysql&logoColor=white)

# APLIKASI PENDAFTARAN PELATIHAN DIGITAL MARKETING BERBASIS WEB

<b>APLIKASI PENDAFTARAN PELATIHAN DIGITAL MARKETING BERBASIS WEB</b>

<p>Dibuat untuk pemenuhan tugas project UAS mata kuliah Web Programming 2</p>

<br>

## Tools / Framework / Other

| Bagian      | Keterangan                                                                       |
| ----------- | -------------------------------------------------------------------------------- |
| Fitur       | Login (Myth/Auth), Create, Read, Update, Delete, Validation, Print, Export excel |
| Framework   | Bootstrap 4, CodeIgniter 4                                                       |
| Text Editor | Visual Studio Code                                                               |

<br>

## Environment

1. Download XAMPP

```bash
https://www.apachefriends.org/index.html
```

2. Download Visual Studio Code

```bash
https://code.visualstudio.com/
```

3. Download Composer

```bash
https://getcomposer.org/
```

4. Download Git

```bash
http://git-scm.com/
```

5. Buat database dengan nama ci4 di local, ketikkan pada browser :

```bash
localhost/phpmyadmin/
```

6. Import database dengan nama ci4.sql

<br>

## Install Codeigniter Melalui Composer

Install Codeigniter 4 dengan nama Website_Pendaftaran_Pelatihan_Digital_Marketing melalui gitbash arahkan pada htdocs

```bash
composer create-project codeigniter4/appstarter Website_Pendaftaran_Pelatihan_Digital_Marketing
```

<br>

## Run Server

1. Pastikan masih berada di dalam folder Website_Pendaftaran_Pelatihan_Digital_Marketing -> Klik kanan pilih gitbash lalu ketikkan :

```bash
$php spark serve
```

2. Buka XAMPP lalu start apache dan mysql
3. Buka browser anda (Tab baru) lalu ketikkan -> localhost:8080 atau sesuaikan yang ada pada gitbash

<br>

## Cara Menjalankan Web Secara Local

1. Download repository ini
2. "Environment" pastikan semua telah dilakukan
3. Lalu buka file XAMPP (php.ini) -> hapus semicolon (;) didepan extension=intl -> save
4. Extract file yang di download tadi -> Copy & Paste isi folder -> XAMP (htdocs) -> masuk kedalam folder Website_Pendaftaran_Pelatihan_Digital_Marketing -> Replace
5. Run server
6. Selesai, selamat menikmati

<br>
