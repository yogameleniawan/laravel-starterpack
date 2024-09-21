<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## Requirement

- [PHP 8.1 or Higher](https://www.php.net/downloads.php)
- [Laravel 11](https://www.laravel.com/)
- [Laragon](https://laragon.org/download/)
- [NodeJS](https://nodejs.org/en)
- [Postman](https://www.postman.com/downloads/)
  
## Installation

1. Buka Terminal
```bash
git clone https://github.com/yogameleniawan/laravel-starterpack.git
```
2. Buka folder hasil clone
```bash
cd laravel-starterpack
```
3. Jalankan Composer Install
```bash
composer install
``` 
4. Jalankan perintah untuk copy .env
```bash
cp .env.example .env
```
5. Jalankan perintah untuk melakukan generate key
```bash
php artisan key:generate
```
6. Jalankan perintah untuk melakukan generate migration
```bash
php artisan migrate
```
Jika terdapat error ketika menjalankan perintah di atas ikuti langkah-langkah di bawah ini :

Buka file `.env`

![image](https://github.com/user-attachments/assets/4468b738-08c8-4c6b-bc67-9a43d2bd3b50)

Pada .env key seperti di bawah ini silahkan sesuaikan dengan database credential sesuai dengan database, username, dan password yang ada pada perangkat temen-temen.

Sebelum

![image](https://github.com/user-attachments/assets/39f9b81f-6c1e-484a-a795-c8aa5835bf39)

Sesudah

![image](https://github.com/user-attachments/assets/2d31dade-f9cb-4399-a845-c28c8efda988)

7. Install npm dependency
```bash
npm install
```
8. Jalankan Laravel
```bash
php artisan serve
```

9. Buka terminal baru di direktori laravel yang sama, kemudiab jalankan javascript bundle
```bash
npm run dev
```

10. Buka pada browser
[127.0.0.0:8000](http://127.0.0.1:8000/)

Hasilnya akan seperti ini 
![image](https://github.com/user-attachments/assets/21c73c13-9c46-4565-9322-db98efc706df)



