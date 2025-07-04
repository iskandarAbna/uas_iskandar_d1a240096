Personal Web
Deskripsi

Studi kasus ini bertujuan untuk membangun sebuah aplikasi web personal yang bersifat dinamis, di mana pemilik web dapat mengelola konten secara mandiri melalui halaman admin. Aplikasi dikembangkan menggunakan PHP dan menyimpan data menggunakan database MySQL. Tampilan antarmuka dirancang menggunakan Tailwind CSS agar responsif, modern, dan mudah dikustomisasi.

Website ini memiliki dua bagian utama:

Halaman Publik, yang dapat diakses oleh semua pengunjung.
Halaman Admin, yang hanya dapat diakses setelah login, digunakan untuk mengelola konten.
Fitur-fitur

Login & Logout (Halaman login admin dengan validasi, Sistem sesi untuk melindungi halaman admin, Logout untuk mengakhiri sesi dengan aman)
Manajemen Artikel (Tambah artikel (judul + isi), Edit artikel yang sudah ada, Hapus artikel, Tampilkan daftar artikel di halaman utama, Sidebar "Daftar Artikel" yang terupdate otomatis)
Manajemen Gallery (Upload gambar beserta judul, Ganti gambar dan judul yang sudah ada, Hapus gambar, Tampilkan gambar di halaman galeri publik dalam grid responsif)
Manajemen About (Tambah deskripsi tentang diri, Edit dan hapus bagian “About”, Tampilkan deskripsi di halaman publik about.php)
Dashboard Statistik Admin (Menampilkan ringkasan jumlah: Artikel & Gambar di gallery)
Halaman Publik yang Rapi & Dinamis (Artikel terbaru ditampilkan otomatis, Galeri responsif dan ringan, Tentang Saya tampil dengan struktur informatif)
Teknologi yang Digunakan

Bahasa Pemrograman : PHP
Database : MySQL
Frontend : Tailwind CSS, HTML
Server Side : Apache / XAMPP
**struktur folder**
![struktur](https://github.com/user-attachments/assets/2e8eaf73-d816-4eec-a4ed-f4d72d7da764)
User Interface Halaman Publik

A. Halaman Home / Artikel

Halaman Home atau Halaman Artikel adalah halaman yang menampilkan daftar artikel dan artikel terbaru.
![Gam1](https://github.com/user-attachments/assets/693f19c2-2ce5-451b-a77a-ae5282695229)
B. Halaman Gallery
Halaman Gallery adalah halaman yang menampilkan foto-foto mahasiswa secara individu.
![gam2](https://github.com/user-attachments/assets/48e2df34-b42f-4523-be96-8b299d6d61f7)
C. Halaman About
Halaman About adalah halaman yang menampilkan deskripsi tentang saya atau profile dari masing-masing mahasiswa.
![gam3](https://github.com/user-attachments/assets/31b01e2e-7a53-43db-bf29-74b10a82eed7)
User Interface Halaman Admin
A. Halaman Login
Halaman Login adalah halaman yang digunakan untuk mengakses halaman admin, diperlukan username dan password.
![gam4](https://github.com/user-attachments/assets/372446ad-9f56-45c5-8e8d-dde5ab7ba7a3)
