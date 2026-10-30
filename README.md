# Aplikasi Sistem Perpustakaan

## 1. Deskripsi Aplikasi
Aplikasi Sistem Perpustakaan merupakan aplikasi desktop berbasis Python yang digunakan untuk membantu pengelolaan data buku dan pengguna perpustakaan. Aplikasi menggunakan pola arsitektur Model-View-Controller (MVC) dan database MySQL untuk menyimpan data.

## 2. Struktur Direktori MVC

- `models/`: Mengelola data dan komunikasi dengan database.
- `views/`: Menampilkan antarmuka aplikasi kepada pengguna.
- `controllers/`: Mengatur proses dan logika antara model dan view.
- `tests/`: Menyimpan file pengujian aplikasi.
- `.github/workflows/`: Menyimpan konfigurasi otomasi CI/CD.
- `main.py`: File utama untuk menjalankan aplikasi.
- `requirements.txt`: Daftar pustaka yang dibutuhkan aplikasi.
- `dist/`: Folder hasil pemaketan aplikasi menjadi file `.exe`.

## 3. Instalasi dan Konfigurasi Database MySQL

1. Instal Python dan Visual Studio Code.
2. Instal Laragon dan jalankan layanan MySQL.
3. Buat database MySQL sesuai nama database yang digunakan dalam kode aplikasi.
4. Sesuaikan konfigurasi koneksi database pada kode proyek, termasuk host, username, password, dan nama database.
5. Instal dependensi aplikasi dengan perintah:

   ```bash
   pip install -r requirements.txt
   ```

## 4. Cara Menjalankan Aplikasi

1. Aktifkan virtual environment jika tersedia.
2. Pastikan layanan MySQL di Laragon sudah berjalan.
3. Buka terminal pada direktori utama proyek.
4. Jalankan perintah berikut:

   ```bash
   python main.py
   ```

5. Untuk menjalankan versi aplikasi desktop yang telah dikemas, buka file `dist/AplikasiPerpustakaan.exe`.