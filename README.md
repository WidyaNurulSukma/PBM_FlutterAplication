# Flutter Module Make News Portal

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Aplikasi Portal Berita Flutter

## Gambaran Umum
Aplikasi portal berita mobile yang dibangun dengan Flutter yang memungkinkan pengguna untuk melihat artikel berita dari berbagai kategori, membaca konten secara detail, dan mengelola autentikasi pengguna. Aplikasi ini mendemonstrasikan konsep-konsep fundamental Flutter termasuk manipulasi widget, integrasi API, alur autentikasi pengguna, dan navigasi.

## Fitur
- **Feed Berita**: Melihat artikel berita terbaru dari API Tech Crunch
- **Pemilihan Kategori**: Menjelajahi berita berdasarkan kategori berbeda (Umum, Hiburan, Transportasi)
- **Detail Artikel**: Membaca artikel lengkap dengan gambar dan tanggal publikasi
- **Autentikasi Pengguna**: Sistem login dan registrasi dengan autentikasi berbasis token
- **Manajemen Profil**: Melihat dan mengelola informasi profil pengguna

## Screenshot
![image](https://github.com/user-attachments/assets/5a693c4c-d4fa-428f-9e1e-f828c521f819)
![image](https://github.com/user-attachments/assets/d66b4add-8a09-4bff-a388-b84abbb4b809)
![image](https://github.com/user-attachments/assets/86c5f16d-5d10-4df4-bb84-3f65f69f75f5)
![image](https://github.com/user-attachments/assets/08df3b8a-614f-4886-a675-8c2f13a4bbb0)


## Teknologi yang Digunakan
- Flutter untuk UI dan logika aplikasi
- Package HTTP untuk integrasi API
- Shared Preferences untuk penyimpanan lokal
- Curved Navigation Bar untuk navigasi kustom
- FlutterToast untuk notifikasi pengguna

## Integrasi API
Aplikasi ini menggunakan API News untuk mendapatkan artikel berita terbaru dari TechCrunch.

## Cara Instalasi
1. Clone repositori ini
2. Jalankan `flutter pub get` untuk menginstal dependensi
3. Jalankan `flutter run` untuk memulai aplikasi

## Struktur Proyek
```
lib/
  ├── main.dart         # Entry point aplikasi
  ├── home.dart         # Halaman beranda menampilkan daftar berita
  ├── detail.dart       # Halaman detail untuk artikel berita
  ├── kategori.dart     # Halaman pemilihan kategori berita
  ├── profil.dart       # Halaman profil pengguna
  ├── formlogin.dart    # Halaman login pengguna
  └── formregist.dart   # Halaman registrasi pengguna
```

## Dibuat untuk
Tugas Mata Kuliah Pengembangan Berbasis Mobile - SINF3044

## Lisensi
Proyek ini dilisensikan di bawah lisensi MIT.
