# AutoSINTA (Sinkronisasi Otomatis SINTA)

## 1. Tentang AutoSINTA

**AutoSINTA** merupakan aplikasi penyinkronisasi otomatis [SINTA Kemdikbud](https://sinta.kemdikbud.go.id) yang ditulis dalam bahasa pemrograman Python. Program ini merupakan ekstensi (tidak resmi) serta pengakses API SINTA yang dapat memudahkan administrator SINTA dalam melakukan pembaruan data publikasi penulis di instansi pendidikan masing-masing. **AutoSINTA** merupakan aplikasi bersumber terbuka yang dapat dimodifikasi oleh siapa saja selama berada dalam batas yang ditentukan oleh lisensi [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0).

**AutoSINTA** dibuat oleh S. Lykamanuella, mahasiswa S1 Fisika Universitas Kristen Satya Wacana (UKSW), dan dipersembahkan untuk Direktorat Riset dan Pengabdian Masyarakat UKSW serta seluruh universitas di Indonesia yang bergantung pada SINTA Kemdikbud dalam menjalankan operasional akademik.

Kunjungi [repositori GitHub AutoSINTA](https://github.com/groaking/autosinta) untuk informasi lebih lanjut.

## 2. Unduhan

|||
|:-:|:-:|
|AutoSINTA v1.0.1 - Windows|[![download-button-plain-4189232584](https://github.com/groaking/groaking.github.io/assets/93555329/75d6c556-1c72-47e2-bfe9-095bafb66238)](https://github.com/groaking/autosinta/releases/download/v1.0.1/autosinta-v1.0.1-pyinstaller-windows.exe)|

## 3. Cara Penggunaan

### 1. Pastikan komputer terhubung ke internet;

### 2. Unduh **AutoSINTA** menggunakan tautan di atas;

### 3. Setelah program biner telah terunduh, jalankan program **AutoSINTA** dengan melakukan klik ganda pada program;

### 4. Jika Windows Defender SmartScreen memunculkan balon, ketuk tombol "Run Anyway";

> *Baca juga [artikel ini](https://www.addictivetips.com/windows-tips/fix-no-run-anyway-option-on-smartscreen-windows-10) untuk mengatasi aplikasi AutoSINTA tidak dapat dijalankan.*

### 5. Setelah **AutoSINTA** dibuka, jendela seperti gambar berikut akan muncul;

![1](https://github.com/groaking/groaking.github.io/assets/93555329/d151b083-5745-4c62-8165-c4b1376a1f71)

### 6. Masukkan kredensial SINTA Author Verificator (AV) Anda pada masukan "Username" dan "Password". Kemudian, klik tombol "LOGIN";

![2](https://github.com/groaking/groaking.github.io/assets/93555329/b2764d89-36d9-4288-813d-f847449364c5)

### 7. Pastikan jendela sebagai berikut muncul;

![3](https://github.com/groaking/groaking.github.io/assets/93555329/5c9aa858-6a5c-4d05-b2b1-30b6a14f8f19)

> *Jika login gagal, pastikan kredensial yang Anda masukkan benar, periksa koneksi internet, lalu coba lagi.*

### 8. Setelah login berhasil, tentukan jenis publikasi yang ingin Anda sinkronisasi

![4](https://github.com/groaking/groaking.github.io/assets/93555329/36cccf57-4e63-40b8-9916-a8f59b4f8db2)

### 9. Ketuk tombol "Load Author List" untuk mendapatkan daftar penulis SINTA Kemdikbud yang dikelola oleh akun AV yang sedang login. Jika pemuatan daftar penulis berhasil, akan muncul dialog sebagai berikut;

![5](https://github.com/groaking/groaking.github.io/assets/93555329/f3375aa5-d148-4440-b626-4dcf8d20a986)

![6](https://github.com/groaking/groaking.github.io/assets/93555329/9d88e503-c706-4e1e-9e3a-a5c44d94937c)

### 10. Klik tombol "Sync". Maka akan muncul jendela sebagai berikut;

![7](https://github.com/groaking/groaking.github.io/assets/93555329/1dd29eff-56e6-4f3c-877e-769978e4bfe9)

### 12. Jika Anda ingin menyinkronisasi data publikasi semua penulis SINTA, pilih opsi "Sync all SINTA authors" lalu klik "SYNC NOW";

### 13. Jika Anda ingin menyinkronisasi data publikasi dari hanya beberapa penulis SINTA, lakukan sebagai berikut:

![8](https://github.com/groaking/groaking.github.io/assets/93555329/c4b1dac5-962e-4ab2-98ea-9b4f6341e035)

- Pilih opsi "Only sync selected authors";
- Pindahkan nama-nama penulis yang akan disinkronisasi dari tabel kiri ke tabel "Authors queued for synchronization" di sebelah kanan;
- Ketuk "SYNC NOW";

### 14. Proses sinkronisasi data publikasi penulis SINTA akan segera berjalan. Tunggu hingga selesai;

![9](https://github.com/groaking/groaking.github.io/assets/93555329/1bb42ff9-38ab-4e33-b86e-c54011899afc)

### 15. Setelah muncul dialog seperti gambar berikut, maka proses sinkronisasi telah selesai.

![10](https://github.com/groaking/groaking.github.io/assets/93555329/a82f9451-65a3-4eae-b5e7-23667bc0e453)

### 16. Anda dapat memastikan di laman [Author Verification](https://sinta.kemdikbud.go.id/authorverification) bahwa data publikasi telah diantrekan untuk sinkronisasi

![11](https://github.com/groaking/groaking.github.io/assets/93555329/784e09b6-43b3-4ba8-a892-e3145368b951)

### 17. Pilih opsi `File > Quit` untuk keluar dari aplikasi AutoSINTA

![11](https://github.com/groaking/groaking.github.io/assets/93555329/0180b3d9-445c-4397-add0-346df8561cdd)
