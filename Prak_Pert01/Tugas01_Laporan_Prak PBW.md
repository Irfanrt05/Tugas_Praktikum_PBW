# Laporan Praktikum Pemrograman Berbasis Web

---
## Identitas
- **Nama**            : Muhammad Irfan Hakim
- **Npm**             : 4523210075
- **Dosen Pengampu**  : Adi Wahyu Pribadi,S.Si.,M.Kom.
  
---
## Deskripsi
Laporan ini berisi rangkuman praktikum git dan github yang meliputi, instalasi git dengan Windows atau Mac,
konfigurasi awal, pembuatan repositori lokal, hingga proses commit, push, pull. tujuannya yaitu untuk memahami
dasar-dasar penggunaan git dan mempelajari cara membuat repository di github

---
## Langkah Pembelajaran
1. Instalasi git
   
   Memastikan git sudah terpasang dengan menjalankan:
   ```bash
   git --version
2. Konfigurasi git

   Memasukkan identitas, agar setiap commit tercatat
   ```bash
   git config --global user.name "Irfan"
   git config --global user.email "Email@gmail.com"
3. Membuat repository lokal

   Buat folder proyek, lalu jalankan:
   ```bash
   git init
4. Membuat repository di Github

   Login ke Github → buat repository baru → dan salin URL repository tersebut.
5. Menghubungkan repository lokal ke Github

   Jalankan perintah:
   ```bash
   git remote add origin <URL-repo>
6. Menambahkan dan commit file

   tambahkan file dengan menjalankan perintah:
   ```bash
   git add .

7. Membuat commit
  
   lalu simpan dengan menjalankan perintah:
   ```bash
   git commit -m "pesan commit"
8. Push ke Github

   unggah commit ke Github dengan:
   ```bash
   git push origin main
9. Pull dari Github

    ambil update terbaru dari Github dengan perintah:
   ```bash
   git pull origin main

---
## Bukti SS Program
<img width="1913" height="1199" alt="Screenshot 2025-09-26 100855" src="https://github.com/user-attachments/assets/10628bdb-865c-4812-95dc-82821809e863" />

## Kesimpulan
Dari praktikum ini kita mengetahui cara menginstall git, membuat repository, melakukan commit, dan menghubungkan repository lokal ke Github.
