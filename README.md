# Panduan PHP Dasar
* [Pengenalan PHP](#1-pengenalan-php)
  + [Sejarah dan tujuan PHP](#Sejarah-dan-tujuan-PHP)
  + [Instalasi PHP](#Instalasi-PHP)
  + [Struktur dasar program PHP](#Struktur-dasar-program-PHP)
  + [Variabel dan tipe data](#Variabel-dan-tipe-data)
* [Pemrograman Dasar](#2-Pemrograman-Dasar)
  + [Operator (aritmatika, perbandingan, logika)](#Operator)
  + [Struktur kontrol](#Struktur-kontrol)
  + [Fungsi dan prosedur](#Fungsi-dan-prosedur)
* [Pengolahan Form](#3-Pengolahan-Form)
  + [Mengirim dan menerima data dari formulir HTML](#Mengirim-dan-menerima-data-dari-formulir-HTML)
  + [Validasi input pengguna](#Validasi-input-pengguna)
  + [Menggunakan metode GET dan POST](#Menggunakan-metode-GET-dan-POST)
* [Manipulasi String](#4-Manipulasi-String)
  + [Manipulasi teks (penggabungan, pemisahan, pemformatan)](#Manipulasi-teks)
  + [Pencarian dan penggantian string](#Pencarian-dan-penggantian-string)
  + [Ekstraksi karakter dan substring](#Ekstraksi-karakter-dan-substring)
* [Penanganan File](#5-Penanganan-File)
  + [Membaca dan menulis file teks](#Membaca-dan-menulis-file-teks)
  + [Manipulasi file (mengganti nama, menghapus)](#Manipulasi-file)
  + [Membaca dan menulis file CSV atau Pdf](#Membaca-dan-menulis-file-CSV-atau-XML)
* [Koneksi ke Database](#6-Koneksi-ke-Database)
  + [Menggunakan MySQL](#Menggunakan-MySQL)
  + [Koneksi ke database](#Koneksi-ke-database)
  + [Mengeksekusi query SQL (SELECT, INSERT, UPDATE, DELETE)](#Mengeksekusi-query-SQL)
* [Session dan Cookies](#7-Session-dan-Cookies)
  + [Session](#session)
  + [Cookies](#cookies)
* [Penanganan Error](#8-Penanganan-error)
  + [Menangani kesalahan dan pengecualian](#Menangani-kesalahan-dan-pengecualian)
  + [Menerapkan mekanisme pemecahan masalah](#Menerapkan-mekanisme-pemecahan-masalah)
* [Pengiriman Email](#9-Pengiriman-Email)
  + [Mengirim email dengan PHP](#Mengirim-email-dengan-PHP)
  + [Menerapkan fungsi-fungsi email](#Menerapkan-fungsi-fungsi-email)
* [Pembuatan Halaman Web Dinamis](#10-Pembuatan-Halaman-Web-Dinamis)
  + [Membuat template halaman dengan PHP](#Membuat-template-halaman-dengan-PHP)
  + [Memisahkan logika dan tampilan](#Memisahkan-logika-dan-tampilan)
  + [Menerapkan penggunaan file terpisah (header, footer, dll.)](#Menerapkan-penggunaan-file-terpisah)
* [Keamanan-Web](#11-Keamanan-Web)
  + [Mencegah serangan injeksi SQL](#Mencegah-serangan-injeksi-SQL)
  + [Melindungi aplikasi dari serangan cross-site scripting (XSS)](Melindungi-aplikasi-dari-serangan-cross-site-scripting)
  + [Menerapkan sanitasi data pengguna](#Menerapkan-sanitasi-data-pengguna)
 
# 1. Pengenalan PHP
  ## Sejarah dan tujuan PHP

Hello sobat koding - Di sini, kita akan menjelajahi sejarah singkat PHP, bagaimana ia lahir, serta tujuan utama di balik keberadaannya. Bersiaplah untuk memahami asal-usul bahasa pemrograman yang telah menjadi tulang punggung jutaan situs web di seluruh dunia!

`Bagian 1: Awal Mula PHP`

PHP, singkatan dari "PHP: Hypertext Preprocessor," bukanlah singkatan yang mudah diingat, tetapi kisahnya sangat menarik. Pada tahun 1994, seorang programmer bernama Rasmus Lerdorf membuatnya untuk mengelola resume pribadinya dan menghitung berapa kali situsnya telah dilihat. Siapa sangka, apa yang dimulai sebagai proyek sederhana ini akan menjadi fenomena dunia web!

Awalnya, PHP disebut "Personal Home Page" (PHP), sebuah alat sederhana yang membantu dalam pengembangan situs web. Tapi, kemudian, PHP berevolusi menjadi "PHP: Hypertext Preprocessor" - menggambarkan peran barunya dalam memproses kode di sisi server untuk menghasilkan konten dinamis yang menakjubkan.

`Bagian 2: Perjalanan PHP Menuju Populeritas`

PHP, seperti biasanya dalam cerita-cerita yang menginspirasi, tidak pernah meraih kesuksesannya dalam semalam. Setelah dirilis ke publik, banyak programmer dan pengembang web tertarik dengan kemampuan dan kegunaan bahasa ini. PHP memungkinkan mereka untuk membuat situs web interaktif, mengambil data dari basis data, dan bahkan membuat forum diskusi. Dalam waktu singkat, web penuh dengan situs-situs yang dibangun dengan PHP!

`Bagian 3: Mengapa PHP Begitu Populer?`

Keistimewaan PHP tidak hanya terletak pada asal-usul dan popularitasnya, tetapi juga pada beberapa tujuan yang menjadikannya bahasa pemrograman yang begitu asik dan bermanfaat:

- Kemudahan Penggunaan: PHP dirancang untuk menjadi mudah dipahami oleh pemula sekalipun. Kode PHP mudah dibaca, ditulis, dan dimengerti, membuatnya menjadi pilihan sempurna bagi para pengembang baru.
- Open-Source dan Gratis: PHP adalah perangkat lunak sumber terbuka yang artinya, semua orang dapat menggunakannya tanpa biaya. Komunitas yang besar dan bersemangat telah membantu mengembangkan PHP menjadi apa yang kita kenal hari ini.
- Dukungan Server Luas: PHP kompatibel dengan banyak server web populer seperti Apache, Nginx, dan IIS. Ini membuatnya dapat berjalan dengan mulus di sebagian besar lingkungan server.
- Kaya Akan Fitur: PHP dilengkapi dengan sejumlah besar fungsi dan library yang siap pakai, memungkinkan pengembang untuk menghemat waktu dan usaha dalam pengembangan.
- Situs Web Dinamis: Dengan PHP, Anda dapat menciptakan situs web dinamis yang menyesuaikan diri dengan pengguna. Interaksi pengguna dengan situs web tidak lagi terbatas hanya pada tampilan statis, namun menjadi lebih menarik dan interaktif.
- Komunitas yang Ramah: PHP memiliki komunitas yang luar biasa, di mana para pengembang saling berbagi pengetahuan, pengalaman, dan dukungan. Jika Anda pernah merasa tersesat dalam kode, selalu ada seseorang yang siap membantu Anda.

`Kesimpulan:`
Dengan sejarah yang menarik dan tujuan yang kuat, PHP telah membuktikan dirinya sebagai bahasa pemrograman yang luar biasa. Memulai petualangan di dunia PHP adalah keputusan yang tepat, apakah Anda seorang pemula atau ahli. Jadi, mulailah belajar PHP dan lihatlah bagaimana Anda dapat menciptakan situs web hebat dan dinamis yang akan memukau pengunjung Anda! Selamat berkoding!

  ## Instalasi PHP
  ## Struktur dasar program PHP
  ## Variabel dan tipe data
# 2. Pemrograman Dasar
