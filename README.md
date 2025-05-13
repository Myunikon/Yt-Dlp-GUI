# Ytt_dlp - Pengunduh Video Berbasis yt-dlp
Ytt_dlp adalah aplikasi desktop yang kuat untuk mengunduh video dari berbagai platform seperti YouTube, Vimeo, dan lainnya. Aplikasi ini dibangun di atas yt-dlp, sebuah fork dari youtube-dl yang menawarkan fitur lebih banyak dan pembaruan yang lebih sering.

## Fitur Utama
- ✅ Unduh dari berbagai platform : YouTube, Vimeo, TikTok, Instagram, Facebook, dan banyak lagi
- ✅ Antarmuka pengguna yang intuitif : Mudah digunakan bahkan untuk pemula
- ✅ Unduhan bersamaan : Unduh beberapa video secara paralel
- ✅ Dukungan format : Pilih format video dan audio yang diinginkan
- ✅ Dukungan subtitle : Unduh subtitle dalam berbagai bahasa
- ✅ Unduhan playlist : Unduh seluruh playlist atau pilih video tertentu
- ✅ Pemantauan performa : Pantau penggunaan sumber daya sistem
- ✅ Penanganan kesalahan : Pesan kesalahan yang ramah pengguna
## Persyaratan Sistem
- Python 3.8 atau lebih baru
- Sistem operasi: Windows, macOS, atau Linux
- Koneksi internet yang stabil
- Minimal 100MB ruang disk kosong
## Instalasi
### Metode 1: Instalasi dari Source
1. Pastikan Python dan pip sudah terinstal di sistem Anda
2. Kloning repositori ini:
   bash
   
   Run
   
   Open Folder
   
   1
   
   2
   
   git clone https://github.com/username/
   
   Ytt_dlp.git
   
   cd Ytt_dlp
3. Instal dependensi yang diperlukan:
   bash
   
   Run
   
   Open Folder
   
   1
   
   pip install -r requirements.txt
4. Jalankan aplikasi:
   bash
   
   Run
   
   Open Folder
   
   1
   
   python -m src.main
### Metode 2: Instalasi dengan Executable (Windows)
1. Unduh file installer terbaru dari halaman releases
2. Jalankan installer dan ikuti petunjuk di layar
3. Setelah instalasi selesai, jalankan Ytt_dlp dari menu Start atau desktop shortcut
## Cara Penggunaan
1. Masukkan URL : Tempel URL video atau playlist yang ingin diunduh
2. Pilih Format : Pilih format video/audio yang diinginkan (mp4, webm, mp3, dll)
3. Pilih Direktori : Tentukan lokasi penyimpanan file hasil unduhan
4. Opsi Tambahan : Sesuaikan pengaturan subtitle, kualitas, dll (opsional)
5. Mulai Unduhan : Klik tombol "Unduh" untuk memulai proses
## Konfigurasi
Ytt_dlp menyimpan konfigurasi di lokasi standar sistem operasi Anda:

- Windows: %APPDATA%\YtdlpGUI\config.json
- macOS: ~/Library/Application Support/YtdlpGUI/config.json
- Linux: ~/.config/YtdlpGUI/config.json
Pengaturan yang dapat dikonfigurasi:

- Direktori unduhan default
- Jumlah unduhan bersamaan maksimum
- Tema aplikasi (terang/gelap)
- Bahasa antarmuka
- Penyimpanan riwayat unduhan
- Kualitas unduhan default
## Domain yang Didukung
Ytt_dlp mendukung unduhan dari berbagai platform, termasuk:

- YouTube (youtube.com, youtu.be)
- Vimeo (vimeo.com)
- Dailymotion (dailymotion.com)
- Twitch (twitch.tv)
- TikTok (tiktok.com)
- Instagram (instagram.com)
- Facebook (facebook.com, fb.watch)
Untuk daftar lengkap domain yang didukung, lihat file config/allowed_domains.txt .

## Pemecahan Masalah
### Masalah Umum
1. yt-dlp tidak ditemukan
   
   - Pastikan yt-dlp terinstal dengan benar: pip install yt-dlp
   - Pastikan yt-dlp ada dalam PATH sistem
2. Unduhan gagal dengan error HTTP
   
   - Periksa koneksi internet Anda
   - Pastikan URL video valid dan dapat diakses
   - Beberapa video mungkin dibatasi secara geografis atau memerlukan login
3. Aplikasi berjalan lambat
   
   - Kurangi jumlah unduhan bersamaan di pengaturan
   - Tutup aplikasi lain yang menggunakan banyak sumber daya
### Log Error
Log aplikasi disimpan di direktori logs/ytdlp_studio.log . Sertakan file log ini saat melaporkan masalah.

## Pengembangan
### Struktur Proyek
plaintext

Open Folder

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

Ytt_dlp/

├── config/                # File

konfigurasi

├── logs/                  # Log

aplikasi

├── src/                   # Kode sumber

│   ├── __init__.py        #

Inisialisasi paket

│   ├── config.py          # Manajemen

konfigurasi

│   ├── download_manager.py # Pengelola

unduhan

│   ├── error_handler.py   # Penanganan

kesalahan

│   ├── loading_indicator.py #

Indikator loading UI

│   ├── main.py            # Entry

point aplikasi

│   └── performance.py     # Pemantauan

performa

├── tests/                 # Unit tests

├── CI_CD_GUIDE.md         # Panduan CI/

CD

├── README.md              #

Dokumentasi utama

└── requirements.txt       # Dependensi

Python

Fold

### Menjalankan Tests
bash

Run

Open Folder

1

pytest tests/

### Kontribusi
Kontribusi sangat diterima! Silakan ikuti langkah-langkah berikut:

1. Fork repositori ini
2. Buat branch fitur baru ( git checkout -b fitur-baru )
3. Commit perubahan Anda ( git commit -m 'Menambahkan fitur baru' )
4. Push ke branch ( git push origin fitur-baru )
5. Buat Pull Request
## Lisensi
Proyek ini dilisensikan di bawah MIT License .

## Kredit
- Dibangun di atas yt-dlp
- Antarmuka pengguna menggunakan Kivy
- Ikon dan aset visual dari Material Design Icons
Dibuat dengan ❤️ oleh Tim Pengembang Ytt_dlp
git clone https://github.com/username/nama-repo.git
cd nama-repo

