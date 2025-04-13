# Panduan Instalasi Laragon & Laravel

Dokumentasi ini menjelaskan cara menginstal **Laragon** sebagai local development environment, serta bagaimana cara menginstal **Laravel** di dalamnya.

---

## Instalasi Laragon

### Langkah Instalasi

1. **Download Laragon**
   - Kunjungi [https://laragon.org/download](https://laragon.org/download)
   - Pilih versi **Full** untuk kebutuhan PHP, Apache, MySQL, dan Laravel
   - <img src="image/laragon.png" alt="laragon instal" width="400">
   
2. **Instalasi**
   - Jalankan installer dan ikuti petunjuknya
   - Contoh direktori instalasi: `C:\laragon`
   - Klik **Next** hingga selesai

3. **Menjalankan Laragon**
   - Buka Laragon
   - Klik tombol **Start All** untuk menjalankan Apache dan MySQL
   - <img src="image/laragonStr.png" alt="laragon start" width="400">

4. **Cek di Browser**
   - Buka `http://localhost` di browser
   - Jika muncul halaman Laragon, maka instalasi berhasil
   - <img src="image/laragonStarting.png" alt="laragon start" width="400">

---

## 🌐 Instalasi Laravel di Laragon

### 📌 Persiapan

Pastikan Laragon sudah berjalan, dan Composer sudah terinstal. Versi Full Laragon biasanya sudah menyertakan Composer.

### ⚙️ Langkah Instalasi Laravel

1. **Buka Terminal Laragon**
   - Buka `Laragon > Terminal`
   - <img src="image/laragonCmd.png" alt="laragon start" width="400">

2. **Masuk ke folder www**
   ```bash
   cd C:\laragon\www
   ```

3. **Instal Laravel menggunakan Composer**
   ```bash
   composer global require laravel/installer
   ```
   <img src="image/laravel.png" alt="laragon start" width="400">
   
4. **Buat Folder Proyek**
   Gantilah `contohApp` dengan nama folder proyek kamu:
   ```bash
   laravel new contohApp
   ```
   <img src="image/laravelFolder.png" alt="laragon start" width="400">

5. **Masuk ke Dalam Folder Proyek**
   Gantilah `contohApp` dengan nama folder proyek kamu:
   ```bash
   cd contohApp
   ```
   <img src="image/cd.png" alt="laragon start" width="400">

6. **Jalankan Laravel**
   ```bash
   php artisan serve
   ```
   <img src="image/laravelServe.png" alt="laragon start" width="400">
   
7. **Akses di Browser**
   Setelah instalasi selesai, buka:
   ```
   http://contohApp.test
   ```
   - Jika muncul halaman welcome Laravel, berarti berhasil 🎉
   - ![Laravel Welcome Page](https://laravel.com/img/logomark.min.svg)

---

## 📌 Referensi

- [Laragon Official Site](https://laragon.org)
- [Laravel Official Docs](https://laravel.com/docs)

---
