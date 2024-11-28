# Bookshelf Apps
Bookshelf Apps adalah aplikasi sederhana berbasis web yang memungkinkan pengguna untuk mengelola daftar buku yang ingin dibaca atau telah selesai dibaca. Aplikasi ini dirancang untuk mempermudah pengguna dalam menyimpan informasi terkait buku, mencari buku, dan memindahkan status buku antara rak *"Belum selesai dibaca"* dan *"Selesai dibaca"*.

## Features
- **Menambahkan Buku Baru**: Pengguna dapat menambahkan buku dengan informasi seperti judul, penulis, tahun, dan status selesai dibaca atau belum.
- **Mencari Buku**: Fitur pencarian yang mempermudah pengguna untuk menemukan buku berdasarkan judul.
- **Mengelola Rak Buku**: 
  - Buku yang belum selesai dibaca akan masuk ke dalam rak *Belum selesai dibaca*.
  - Buku yang telah selesai dibaca dapat dipindahkan ke rak *Selesai dibaca* dan sebaliknya.
- **Penyimpanan Data Lokal**: Data buku disimpan menggunakan LocalStorage sehingga tetap tersimpan meskipun halaman direfresh.

## Tech Stack
- **HTML**: Untuk struktur halaman web.
- **CSS**: Untuk mendesain tampilan antarmuka yang responsif dan menarik.
- **JavaScript**: 
  - Mengelola logika aplikasi seperti menambahkan, memindahkan, mencari, dan menyimpan data buku.
  - Menggunakan DOM Manipulation untuk membuat aplikasi interaktif.
  - Memanfaatkan LocalStorage untuk menyimpan data buku secara lokal di browser.

## Project Preview
Input Informasi Buku
![image](https://github.com/user-attachments/assets/22e4d4f1-3b6b-4e60-8fda-3fea9f490545)
List Buku
![image](https://github.com/user-attachments/assets/1b5aa0dc-38da-46c4-b416-65fbf741f7c7)


## How to Run
1. Clone repository ini ke lokal Anda.
   ```bash
   git clone https://github.com/nabilaalt/BookShellApps.git
   ```
2. Buka file `index.html` menggunakan browser Anda.
3. Mulai gunakan aplikasi untuk menambahkan buku baru, mencari buku, dan mengelola rak buku.
