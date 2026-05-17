꒷꒦︶꒷꒦︶ ๋ ࣭ ⭑꒷꒦

# 📖 𝓩𝓲𝓮𝓖𝓾𝓮𝓼𝓽𝓑𝓸𝓸𝓴 ⋅˚₊‧ ୨🕮୧ ‧₊˚ ⋅

[![PHP](https://img.shields.io/badge/PHP-7%20%2F%208-blue?logo=php)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/Database-MySQL%2FMariaDB-orange?logo=mysql)](https://www.mysql.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-4-purple?logo=bootstrap)](https://getbootstrap.com/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

⋆.˚ ────୨ৎ──── ⋆.˚

𐙚‧₊˚📒✩ ₊˚☁️⊹♡

Sebuah aplikasi **Buku Tamu Digital** berbasis web menggunakan **PHP + MySQL** dengan tampilan modern dari **SB Admin 2**.  
Aplikasi ini memungkinkan pencatatan tamu, manajemen data, hingga pembuatan laporan dalam format **Excel** menggunakan **PhpSpreadsheet**.

°‧ 𓆝 𓆟 𓆞 ·｡

## 🚀 Fitur Utama ✎ᝰ.📓🗒 ˎˊ˗
- **Formulir Buku Tamu:** Pengunjung dapat mengisi data seperti nama, email, pesan, dan waktu kunjungan secara langsung melalui antarmuka web.
- **Penyimpanan Data Otomatis:** Setiap entri tamu disimpan ke database secara *real-time* untuk kemudahan pengelolaan dan pencatatan.
- **Tampilan Responsif:** Desain antarmuka yang ramah pengguna dan responsif di berbagai perangkat, baik desktop maupun mobile.
- **Validasi Formulir:** Sistem validasi input untuk memastikan data yang dikirimkan lengkap dan sesuai format.
- **Panel Admin:** Admin dapat melihat, menghapus, atau mengelola data tamu melalui halaman *backend*.
- **Keamanan Dasar:** Perlindungan terhadap spam dan input berbahaya dengan sanitasi data dan penggunaan metode POST.

°‧ 𓆝 𓆟 𓆞 ·｡

### 🔐 Autentikasi Login ⋆˚꩜｡
- Akses aplikasi hanya untuk user yang login  
- *Session management* untuk keamanan

°‧ 𓆝 𓆟 𓆞 ·｡

### 📑 Manajemen Buku Tamu 𐙚‧₊˚📜✩ ₊˚⊹♡
- Tambah, ubah, dan hapus data tamu  
- Data yang disimpan meliputi:  
  - Tanggal kunjungan  
  - Nama tamu  
  - Alamat  
  - Nomor HP/Telp  
  - Bertemu dengan  
  - Kepentingan

°‧ 𓆝 𓆟 𓆞 ·｡

### 📊 Laporan Tamu ‧₊˚🖇️✩ ₊˚📖
- Filter laporan berdasarkan periode tanggal  
- Data laporan ditampilkan dalam tabel interaktif  
- Ekspor laporan ke file **Excel** dengan sekali klik  

°‧ 𓆝 𓆟 𓆞 ·｡

### 🎨 UI Modern
- Menggunakan template **SB Admin 2 (Bootstrap 4)** - Sidebar navigasi responsif (dengan toggle untuk desktop & mobile)  
- Tabel interaktif dengan **DataTables** °‧ 𓆝 𓆟 𓆞 ·｡

## 🛠️ Teknologi yang Digunakan 💻⋆✴︎˚｡⋆
- **Backend:** PHP 7 / 8  
- **Database:** MySQL / MariaDB  
- **Frontend:** Bootstrap 4 (SB Admin 2 Template)  
- **Library:** - [PhpSpreadsheet](https://phpspreadsheet.readthedocs.io/) → ekspor laporan ke Excel  
  - [FontAwesome](https://fontawesome.com/) → ikon  
  - [jQuery](https://jquery.com/) & [DataTables](https://datatables.net/) → tabel interaktif  

⊹ ࣪ ﹏𓊝﹏𓂁﹏⊹ ࣪ ˖

## 📂 ˗ˏˋ ꒰ Struktur Folder Utama ✉︎ ꒱ ˎˊ˗🪐✨

```bash
nssyyayy-ZieGuestBook/
├── assets/                 # CSS, JS, gambar
│   ├── css/                # Custom CSS (sb-admin-2.min.css, dll.)
│   ├── js/                 # Script utama (sb-admin-2.min.js, dll.)
│   ├── vendor/             # Library tambahan (Bootstrap, FontAwesome, DataTables)
├── templates/              # Template header & footer
├── vendor/                 # Composer packages (PhpSpreadsheet, dll.)
├── connection.php          # Koneksi database
├── function.php            # Fungsi helper (query, tambah data, dll.)
├── login.php               # Halaman login
├── logout.php              # Logout & destroy session
├── index.php               # Dashboard
├── buku-tamu.php           # CRUD buku tamu
├── users.php               # Manajemen user
├── laporan.php             # Halaman laporan tamu
├── export-laporan.php      # Export laporan ke Excel
└── composer.json           # Konfigurasi Composer
```
---

<div align="center">
  <p><i>Developed with 🤍 and attention to detail.</i></p>
  <p><b>© 2026 Nesya Kirani Nurroffi. All rights reserved.</b></p>
</div>
