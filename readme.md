# Cara Instalasi Projects

## Requirements
- node js & npm [(Download disini)](https://nodejs.org/en)
- php >= v8.2
- mysql

## Cara Install
1. buka PhpMyAdmin, kemudian buat database dengan nama "laravel_absen", atau nama yang lain
2. Setelah itu, extract project yang diberikan
3. Buka folder tersebut menggunakan VSCode atau code editor lain
4. Buka file .env, pastikan konfigurasi database sudah benar, jika ada menggunakan xampp dan nama database yang anda buat adalah "laravel_absen", harusnya konfigurasi anda seperti ini :
   ```dotenv
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=laravel_absen
    DB_USERNAME=root
    DB_PASSWORD=
    ```
5. Buka terminal di vscode dengan cara klik menu `View > Terminal` atau tekan tombol `` Ctrl+` ``
6. Setelah itu jalankan perintah
   ```bash
   php artisan serve
   ```
7. Kemudian buka terminal baru dengan mengklik tombol `+` atau tekan tombol `` Ctrl+Shift+` ``
   ```bash
   npm run dev
   ```
8. Project anda akan berjalan di `http://localhost:8000`