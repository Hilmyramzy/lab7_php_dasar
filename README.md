========================Praktikum 7: PHP Dasar=========================


Tujuan
1. Mahasiswa mampu memahami konsep dasar Server Side Scripting.
2. Mahasiswa mampu memahami dasar Pemrograman PHP.
3. Mahasiswa mampu memahami Variable dan Tipe Data pada PHP
4. Mahasiswa mampu memahami konsep Struktur Kondisi dan Perulangan.
5. Mahasaswa mampu membuat program PHP sederhana.

========================================================================

Pengantar PHP

PHP adalah singkatan dari PHP Hypertext Prepocessor dan merupakan bahasa
pemrograman yang di desain khusus untuk web development atau pengembangan web.

PHP memiliki sifat Server-Side karena PHP dijalankan atau di eksekusi dari sisi server.
maksud di jalankan dari sisi server adalah PHP di jalankan pada komputer server dan
bukan pada komputer client.

PHP di jalankan melalui aplikasi web browser sama halnya
seperti HTML. Hampir semua situs-situs besar dan populer di kembangkan menggunakan
PHP. 

seperti misalnya wordpress, joomla, facebook, twitter, wikipedia dan situs besar
lainnya.

==========================================================================

Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab7_php_dasar pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

   
Langkah-langkah Praktikum
Persiapan
Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP
terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7.
Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu
XAMPP.

Install XAMPP

Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi
portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan
direktorinya (misal: d:\xampp).


=================================================================

Konfigurasi Web Server

• Konfigurasi Apache
Untuk konfigurasi HTTP server, seperti port yang digunakan akses HTTP, modul
yang diaktifkan, lokasi document root, dll.
Lokasi file: \xampp\apache\conf\httpd.conf

• Konfigrasi PHP
Untuk konfigurasi perilaku engine PHP yang berefek pada keamanan dan performa.
Seperti batas maksimal waktu eksekusi script, batas file yang dapat diupload, error
reporting, dll.
Lokasi file: \xampp\php\php.ini

• Konfigrasi MySql

Konfigurasi server MySQL, seperti administrator user, port, timezone, dll.

Lokasi file: \xampp\mysql\bin\my.ini

======================================================================================
Menjalankan Web Server
Untuk menjalankan web server dari menu XAMPP Control.

• Uji coba apakah server sudah berkerja dengan baik
http://127.0.0.1 atau http://localhost
Tampil halaman utama XAMPP jika server sudah berkerja dengan baik.

• Dokumen Website
Semua file website tempatkan di direktori: \xampp\htdocs\

• Database MySQL
Direktori: \xampp\mysql\
Manajemen database: http://localhost/phpmyadmin
