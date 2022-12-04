<p align="center">
  <a href="https://getstisla.com">
    <img src="https://raw.githubusercontent.com/muhammedia/mabar/main/image/logo.png" alt="Mabar logo" width="75" height="75">
  </a>
</p>

<h1 align="center">Mabar</h1>

<span align="center">

**Mabar** adalah sebuah program yang dibangun menggunakan framework Laravel 9 dengan tujuan untuk memudahkan anda dalam mengelola, mengatur dan mengawasi segala hal mengenai pembelian barang dari supplier, stock opname, memantau jumlah pesanan pelanggan, hingga pembuatan laporan secara otomatis dan efisien.

[![](https://img.shields.io/badge/Berikan-Apresiasi-red)](https://trakteer.id/anteikudevs?quantity=1)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/muhammedia/mabar/blob/main/LICENSE)
[![](https://img.shields.io/badge/Developer%20by-Muham-purple)](https://anteiku.tech/)

</span>

[![Mabar Preview](https://raw.githubusercontent.com/muhammedia/mabar/main/image/home.png)](https://anteiku.tech/)

<br>

## Quick Start
### Panduan Penggunaan

Berikut adalah ini adalah panduan cara mengunduh kedalam local path anda.

<details><summary><b>Lihat Panduan</b></summary>

- Clone repo ini melalui **[Git Bash](https://git-scm.com/downloads)** : `git clone https://github.com/muhammedia/mabar.git`
- Ekstrak file **mabar.zip** yang sudah kalian clone melalui tautan diatas ini
- Done

</details>

## File Konfigurasi

Sebelum anda memulai menjalankan program, pastikan bahwa sudah memiliki [XAMPP](https://www.apachefriends.org/download.html) atau [Laragon](https://laragon.org/) yang sudah terinstall pada komputer yang anda gunakan.
### Konfigurasi Database

1. Start Apache & MySQL pada [XAMPP](https://www.apachefriends.org/download.html) atau [Laragon](https://laragon.org/).
2. Akses tautan berikut ini pada browser yang kalian gunakan : `http://localhost/phpmyadmin/`.
3. Buat database baru menggunakan nama **db_mabar.**
4. Buka file `.env` dan isi konfigurasi database pada kode didalam ini. Anda juga dapat mengganti nama database pada kode `DB_DATABASE=nama_databasemu`.
```diff
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_mabar
DB_USERNAME=root
DB_PASSWORD=
```

### Panduan Instalasi

Berikut ini adalah panduan cara menjalankan program dalam komputer yang anda miliki. Pastikan bahwa anda sudah melakukan konfigurasi dan sudah membuat database yang dibutuhkan. Lihat [Konfigurasi Database](#file-konfigurasi)

<details><summary><b>Lihat Panduan</b></summary>

- Pastikan anda sudah memiliki code editor [Visual Studio Code](https://code.visualstudio.com/) (Rekomendasi).
- Buka folder **mabar** menggunakan **Visual Studio Code**.
- Buka **Terminal** pada menu bagian atas **Visual Studio Code** atau anda bisa menggunakan shortcut *CTRL+SHIFT+`*.
- Jalankan perintah berikut `php artisan migrate` setelah berhasil maka jalankan perintah kedua `php artisan db:seed --class StudentSeeder`.
- Jalankan perintah `php artisan serve` dan akses IP `http://127.0.0.1:8000` pada browser yang kalian gunakan.
- Done

</details>

## Team Developer

- **[Muhammad Mauribi](https://facebook.com/muhampedia) (Full Stack Developer)**
- **Novita Nanda Sari (Designer)**
- **Diana Anggi Safitri (Front End)**
- **Kayla Zahrani Amadhita (Front End)**

## Disclaimer

Aplikasi ini masih dalam tahap pengembangan! Jika anda berminat untuk ikut serta mengembangkan projek **Manajemen Barang** silahkan <a href="mailto:muhampedia.id@gmail.com">hubungi kami</a>.

## License

**Mabar** dilisensikan di bawah [MIT License](LICENSE)