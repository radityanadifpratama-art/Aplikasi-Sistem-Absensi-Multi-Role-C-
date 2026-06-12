# Aplikasi Sistem Absensi Multi-Role (C++)

Aplikasi ini adalah sistem manajemen kehadiran digital berbasis *Command Line Interface* (CLI) yang dirancang menggunakan bahasa C++. Sistem ini mengimplementasikan fitur keamanan tingkat lanjut seperti *hash password* dan pembagian hak akses (*multi-role*) yang memisahkan modul halaman antara **Guru** dan **Siswa**.

## 🛠️ Fitur Utama Sistem
* **Autentikasi & Keamanan:** Fitur registrasi akun baru dan sistem login aman dengan enkripsi (*hashing*) password serta pembatasan *counter* login (maksimal 5x gagal).
* **Dashboard Guru (Manajemen Penuh):**
    * Input data absensi harian/mingguan dilengkapi validasi logika tanggal untuk mencegah salah input.
    * Melihat rekapitulasi kehadiran (Hadir/Izin/Sakit/Alfa) seluruh siswa.
    * Hak akses penuh untuk mengubah, menghapus data absensi, serta memodifikasi akun siswa.
* **Dashboard Siswa (Akses Mandiri):**
    * Melihat riwayat absensi pribadi secara *real-time* berdasarkan ID Siswa.
    * Mengubah data profil mandiri (nama, password, dan nomor telepon).

## 💻 Teknologi & Konsep C++ yang Digunakan
* **Bahasa Pemrograman:** C++ Standard Library.
* **Struktur Data & Logika:** *Multi-role Authentication*, *Input Validation*, *Looping & Conditional Statement* (Percabangan Menu), dan *Array/Struct* untuk manajemen data.
* **Konsep Pemrograman:** Modularisasi Fungsi (membagi kode ke dalam fungsi-fungsi kecil agar rapi) dan pemrograman berbasis objek (*Object-Oriented Programming*).

## ⚙️ Lingkungan Pengembangan (Environment)
* **Compiler:** GCC / MinGW
* **Interface:** Terminal / Console Application (CLI)
