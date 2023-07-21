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

Hello sobat koding -  yuk kita bahas sejarah singkat PHP, dari awal mula harinya PHP hinggga kenapa PHP masih populer sampai saat ini!

`Bagian 1: Awal Mula PHP`

PHP, singkatan dari "PHP: Hypertext Preprocessor," yang awal mulanya terjadi pada tahun 1994, yaitu seorang programmer bernama Rasmus Lerdorf membuat sebuah website yang digunakan untuk mengelola resume pribadinya dan menghitung berapa kali situsnya telah dilihat. 

Awalnya, PHP merupakan singkatan dari "Personal Home Page" (PHP), menggambarkan perannya sebagai alat bantu dalam membangun halaman web pribadi. Namun, seiring waktu, fokus PHP berubah dari sekadar halaman pribadi menjadi bahasa pemrograman yang mampu memproses kode di sisi server dan menghasilkan konten dinamis di situs web. Inilah alasan di balik perubahan nama PHP menjadi "PHP: Hypertext Preprocessor."

`Bagian 2: Perjalanan PHP Menuju Populeritas`

Setelah dirilis ke publik oleh Rasmus Lerdorf, PHP tidak segera mencapai kesuksesan besar dalam semalam. Namun, seiring berjalannya waktu, banyak programmer dan pengembang web mulai melihat potensi dan manfaat dari bahasa pemrograman ini.

Salah satu keunggulan utama PHP adalah kemampuannya untuk menciptakan situs web yang interaktif dan dinamis. Dengan PHP, para pengembang dapat memproses data di sisi server, yang berarti mereka dapat menghasilkan halaman web dengan konten yang berubah-ubah sesuai dengan tindakan pengguna atau data dari sumber lain. Ini membuka peluang baru dalam menghadirkan pengalaman yang lebih menarik bagi pengunjung situs.

Seiring dengan semakin banyaknya proyek-proyek situs web yang sukses menggunakan PHP, popularitas bahasa pemrograman ini pun meroket. Komunitas pengembang PHP tumbuh dengan pesat, saling berbagi pengetahuan dan sumber daya, serta menciptakan berbagai ekstensi dan library untuk mendukung pengembangan aplikasi web lebih lanjut.

`Bagian 3: Mengapa PHP Begitu Populer?`

- Kemudahan Penggunaan: PHP dirancang dengan sintaks yang sederhana dan mudah dipahami, membuatnya cocok untuk pemula yang baru belajar pemrograman. Kode PHP mudah dibaca, ditulis, dan dimengerti, sehingga para pengembang baru dapat dengan cepat menguasai bahasa ini dan mulai membangun situs web yang dinamis.

- Open-Source dan Gratis: PHP merupakan perangkat lunak sumber terbuka, yang berarti kode sumbernya dapat diakses oleh siapa pun secara bebas. Selain itu, PHP juga tersedia secara gratis untuk digunakan, tidak ada biaya lisensi yang harus dibayar. Hal ini membuatnya menjadi pilihan populer bagi berbagai kalangan, dari pengembang independen hingga perusahaan besar.

- Dukungan Server Luas: PHP dapat berjalan pada berbagai server web populer seperti Apache, Nginx, dan IIS. Kompatibilitasnya yang luas memungkinkan para pengembang untuk memilih server yang sesuai dengan kebutuhan mereka, tanpa harus terbatas pada satu platform tertentu.

- Kaya Akan Fitur: PHP dilengkapi dengan sejumlah besar fungsi dan library yang siap pakai. Ini memungkinkan pengembang untuk mengakses berbagai fitur dan alat yang telah tersedia, sehingga dapat menghemat waktu dan usaha dalam pengembangan aplikasi web. PHP juga mendukung berbagai format data dan protokol, seperti XML, JSON, dan HTTP, yang memperluas kinerjanya.

- Situs Web Dinamis: Salah satu kekuatan utama PHP adalah kemampuannya untuk menciptakan situs web dinamis. Dengan memproses kode di sisi server, PHP dapat menyesuaikan konten dan tampilan situs sesuai dengan tindakan pengguna atau data yang diperoleh dari sumber lain. Interaksi pengguna dengan situs web menjadi lebih menarik dan responsif.

- Komunitas yang Luas: Komunitas PHP sangat aktif dan bersemangat. Para pengembang PHP dari seluruh dunia saling berbagi pengetahuan, pengalaman, dan sumber daya melalui forum, grup, dan konferensi. Jika seorang pengembang menghadapi masalah atau kesulitan, selalu ada seseorang di komunitas yang siap membantu dan memberikan dukungan.

  ## Instalasi PHP
  ## Struktur dasar program PHP
  ## Variabel dan tipe data
# 2. Pemrograman Dasar
