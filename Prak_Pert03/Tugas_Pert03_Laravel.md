# Laporan Praktikum Pemrograman Berbasis Web

---
## Identitas
- **Nama**            : Muhammad Irfan Hakim
- **Npm**             : 4523210075
- **Dosen Pengampu**  : Adi Wahyu Pribadi,S.Si.,M.Kom.
  
---
## Deskripsi
Laporan ini berisi rangkuman praktikum yang meliputi, instalasi laravel dengan composer, membuat halaman statis,
membuat file view, dan menjalankan server development lokal.

---
## Langkah Pembelajaran
1. Menjalankan perintah untuk instalasi Laravel
   ```bash
   composer create-project laravel/laravel LaraPress

2. Masuk ke direktori yang sudah dibuat
   <img width="1092" height="56" alt="LARA1" src="https://github.com/user-attachments/assets/f6281476-06c3-4f11-98a7-73ade8a91e39" />
   ```bash
   cd LaraPress

3. Jalankan Server Artisan
   <img width="1089" height="282" alt="Screenshot 2025-10-03 110142" src="https://github.com/user-attachments/assets/eb598fda-9426-4dbd-b710-c54fbc29cc05" />
   ```bash
   php artisan serve

4. Buka browser dengan alamat
   ```bash
   http://127.0.0.1:8000

5. Buka folder LaraPress menggunakan VS Code dan buka file routes/web.php
   ```bash
   use Illuminate\Support\Facades\Route;
   Route::get('/', function () {
   return view('welcome');
   });

6. Mengubah file view di resources/views/welcome.blade.php dan di ganti dengan kode
   ```bash
   
    <!DOCTYPE html>
    <html>
    <head>
        <title>Selamat Datang di LaraPress</title>
    </head>
    <body>
        <h1>Selamat Datang di Blog LaraPress</h1>
        <p>Ini adalah halaman utama dari aplikasi blog kita.</p>
    </body>
    </html>

7. Simpan file  welcome.blade.php dan refresh browser http://127.0.0.1:8000
   <img width="687" height="198" alt="Screenshot 2025-10-03 144543" src="https://github.com/user-attachments/assets/51c42580-8591-4725-8fa4-8d2aeb674711" />

8. Membuat halaman baru Tentang Kami
9. Buka kembali file routes/web.php, lalu tambahkan
   ```bash
   Route::get('/tentang-kami', function () {
   return view('about'); // Kita akan menampilkan view bernama 'about'
   });

10. Buat file view baru, didalam folder resources/views/, buat file baru bernama about.blade.php, dan isi dengan html berikut
    ```bash
    
    <!DOCTYPE html>
    <html>
    <head>
        <title>Tentang Kami - LaraPress</title>
    </head>
    <body>
        <h1>Tentang LaraPress</h1>
        <p>LaraPress adalah sebuah proyek blog sederhana yang dibuat untuk mempelajari dasar-dasar framework Laravel 12.</p>
    </body>
    </html>

11. Uji coba halaman di browser dengan
    <img width="974" height="196" alt="Screenshot 2025-10-03 145435" src="https://github.com/user-attachments/assets/b963fc60-5bcf-46cc-8726-5b52d46b5fc3" />
    ```bash
    http://127.0.0.1:8000/tentang-kami

12. Menambahkan link navigasi
    - Di welcome.blade.php, tambahkan di bawah paragraf:
      ```bash
      <a href="/tentang-kami">Lihat Halaman Tentang Kami</a>

      
    - Di about.blade.php, tambahkan di bawah paragraf:
      ```bash
      <a href="/">Kembali ke Halaman Utama</a>

13. Lalu simpan

## Tugas Mandiri
Membuat halaman kontak, yang bisa di akses dengan URL, Isi halaman tersebut dengan informasi kontak fiktif (misal: email dan nomor telepon), dan Jangan lupa tambahkan link navigasi ke dan dari halaman "Kontak" di halaman lainnya.



<img width="692" height="363" alt="Screenshot 2025-10-03 150642" src="https://github.com/user-attachments/assets/480c1086-f374-4105-86cb-d90dde05fe7a" />




   
  



