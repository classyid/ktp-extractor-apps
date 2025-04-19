# KTP Extractor Apps

![KTP Extractor Banner](https://via.placeholder.com/800x200/3b82f6/ffffff?text=KTP+Extractor+Apps)

## 📝 Deskripsi

KTP Extractor Apps adalah aplikasi web berbasis Google Apps Script yang memungkinkan pengguna untuk mengunggah gambar KTP, mengekstrak data secara otomatis menggunakan API OCR, menyimpan hasil ke Google Spreadsheet, dan menampilkan visualisasi statistik. Aplikasi ini ideal untuk organisasi yang perlu mengelola data identitas dalam jumlah besar dengan cepat dan efisien.

## ✨ Fitur Utama

- 📷 Unggah gambar KTP melalui antarmuka drag & drop
- 🔍 Ekstraksi otomatis data KTP menggunakan API OCR
- 📊 Visualisasi statistik real-time (demografi, jenis kelamin, pekerjaan, dll)
- 🔎 Pencarian data KTP berdasarkan NIK atau nama
- 💾 Penyimpanan gambar KTP ke Google Drive
- 📋 Penyimpanan dan organisasi data ke Google Spreadsheet
- 📱 Antarmuka responsif untuk desktop dan mobile
- 🎨 UI modern dengan Tailwind CSS dan Font Awesome

## 🚀 Cara Menggunakan

### Prasyarat

1. Akun Google
2. Akses ke Google Apps Script
3. API key untuk layanan ekstraksi KTP (atau gunakan API yang disediakan)

### Instalasi Cepat

1. Buka [Google Apps Script](https://script.google.com)
2. Buat project baru
3. Copy-paste kode dari file-file berikut ke project Anda:
   - `Code.gs`
   - `Index.html`
   - `CSS.html`
   - `JavaScript.html`
4. Simpan project
5. Deploy sebagai aplikasi web
6. Buka URL aplikasi yang dihasilkan

### Konfigurasi

1. Pada aplikasi, buka tab "Pengaturan"
2. Masukkan ID Google Spreadsheet Anda (atau buat spreadsheet baru)
3. (Opsional) Sesuaikan URL API ekstraksi KTP jika menggunakan layanan sendiri
4. Simpan pengaturan

## 📊 Struktur Spreadsheet

Aplikasi akan membuat spreadsheet dengan tiga sheet:

1. **Master_KTP** - Menyimpan semua data KTP lengkap
2. **NIK** - Menyimpan referensi cepat NIK dan nama
3. **Demografi** - Menyimpan data untuk analisis demografis

## 🛠️ Teknologi yang Digunakan

- Google Apps Script
- HTML/CSS/JavaScript
- Tailwind CSS
- Chart.js
- Font Awesome
- Google Drive & Spreadsheet API

## 📝 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## 🤝 Kontribusi

Kontribusi, issue, dan permintaan fitur sangat diterima!

## 📧 Kontak

[Andri Wiratmono] - [kontak@classy.id]
