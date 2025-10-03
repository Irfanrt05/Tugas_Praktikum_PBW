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
   


   
  



