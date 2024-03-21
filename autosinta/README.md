# AutoSINTA (Sinkronisasi Otomatis SINTA)

## 1. Tentang AutoSINTA

**AutoSINTA** merupakan aplikasi penyinkronisasi otomatis [SINTA Kemdikbud](https://sinta.kemdikbud.go.id) yang ditulis dalam bahasa pemrograman Python. Program ini merupakan ekstensi (tidak resmi) serta pengakses API SINTA yang dapat memudahkan administrator SINTA dalam melakukan pembaruan data publikasi penulis di instansi pendidikan masing-masing. **AutoSINTA** merupakan aplikasi bersumber terbuka yang dapat dimodifikasi oleh siapa saja selama berada dalam batas yang ditentukan oleh lisensi [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0).

**AutoSINTA** dibuat oleh S. Lykamanuella, mahasiswa S1 Fisika Universitas Kristen Satya Wacana (UKSW), dan dipersembahkan untuk Direktorat Riset dan Pengabdian Masyarakat UKSW serta seluruh universitas di Indonesia yang bergantung pada SINTA Kemdikbud dalam menjalankan operasional akademik.

Kunjungi [repositori GitHub AutoSINTA](https://github.com/groaking/autosinta) untuk informasi lebih lanjut.

## 2. Unduhan

[Unduh AutoSINTA v1.0.1 - Windows x64](https://github.com/groaking/autosinta/releases/download/v1.0.1/autosinta-v1.0.1-pyinstaller-windows.exe)

## 3. Cara Penggunaan

### 1. Pastikan komputer terhubung ke internet;

### 2. Unduh **AutoSINTA** menggunakan tautan di atas;

### 3. Setelah program biner telah terunduh, jalankan program **AutoSINTA** dengan melakukan klik ganda pada program;

### 4. Jika Windows Defender SmartScreen memunculkan balon, ketuk tombol "Run Anyway";

> *Baca juga [artikel ini](https://www.addictivetips.com/windows-tips/fix-no-run-anyway-option-on-smartscreen-windows-10) untuk mengatasi aplikasi AutoSINTA tidak dapat dijalankan.*

### 5. Setelah **AutoSINTA** dibuka, jendela seperti gambar berikut akan muncul;

### 6. Perhatikan bahwa pada jendela aplikasi **AutoSINTA**, terdapat tiga tombol seperti gambar berikut;

### 7. Masukkan kredensial SINTA Author Verificator (AV) Anda pada masukan "Username" dan "Password";

### 8. Klik tombol "Verificator Login" seperti ditunjukkan oleh langkah 6. Pastikan jendela sebagai berikut muncul;

> *Jika login gagal, pastikan kredensial yang Anda masukkan benar, periksa koneksi internet, lalu coba lagi.*

### 9. Setelah login berhasil, tentukan jenis publikasi yang ingin Anda sinkronisasi

### 10. Ketuk tombol "Load Author List" untuk mendapatkan daftar penulis SINTA Kemdikbud yang dikelola oleh akun AV yang sedang login. Jika pemuatan daftar penulis berhasil, akan muncul dialog sebagai berikut;

### 11. Klik tombol "Sync". Maka akan muncul jendela sebagai berikut;

### 12. Jika Anda ingin menyinkronisasi data publikasi semua penulis SINTA, pilih opsi "Sync all SINTA authors" lalu klik "SYNC NOW";

### 13. Jika Anda ingin menyinkronisasi data publikasi dari hanya beberapa penulis SINTA, lakukan sebagai berikut:

- Pilih opsi "Only sync selected authors";
- Pindahkan nama-nama penulis yang akan disinkronisasi dari tabel kiri ke tabel "Authors queued for synchronization" di sebelah kanan;
- Ketuk "SYNC NOW";

### 14. Proses sinkronisasi data publikasi penulis SINTA akan segera berjalan. Tunggu hingga selesai;

### 15. Setelah muncul dialog seperti gambar berikut, maka proses sinkronisasi telah selesai.

### 16. Pilih opsi `File > Exit` untuk keluar dari aplikasi AutoSINTA
