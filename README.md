# Multi-auth-login
Multi role auth login dengan Laravel 11 Breeze

Deskripsi Program
Program aplikasi web berbasis Laravel yang menggunakan Laravel Breeze untuk otentikasi multi-pengguna. Aplikasi ini memiliki dua jenis pengguna: Admin dan User. Setiap jenis pengguna memiliki hak akses dan tampilan yang berbeda.

Fitur Utama:
Otentikasi Multi-Pengguna:
Admin dan User memiliki halaman dashboard yang berbeda.
Middleware khusus untuk memeriksa tipe pengguna sebelum mengakses halaman tertentu.

Manajemen Produk (Admin):
Admin dapat mengelola produk melalui halaman khusus.

Halaman Favorit (User):
User dapat melihat daftar favorit mereka.

Petunjuk Singkat Penggunaan Aplikasi
1. Persiapan Proyek
Clone Repository
   git clone <URL_REPOSITORY_GITHUB>
   cd <NAMA_FOLDER_PROYEK>
2. Install Dependencies
    composer install
    npm install
3. Copy .env File
    cp .env.example .env
4. Generate Application Key
   php artisan key:generate
5. Set Up Database
    Edit file .env dan sesuaikan konfigurasi database:
6. Migrate Database
   php artisan migrate
7. Install Laravel Breeze
   composer require laravel/breeze --dev
   php artisan breeze:install
   npm run dev
8. Run Server
   php artisan serve
   ![register](https://github.com/user-attachments/assets/d8e1689a-d075-4541-9b66-6f422bdbcdf4)
   ![admin page](https://github.com/user-attachments/assets/7009418f-3590-430b-9507-89384162d6eb)
   ![user dashboard](https://github.com/user-attachments/assets/70f8e586-37a9-461f-8c97-50330be80d94)
   ![homepage](https://github.com/user-attachments/assets/73e839c3-9aac-41bd-81d4-ee38b6b3abf6)
   ![contac](https://github.com/user-attachments/assets/a8157451-0b88-4d63-aa21-66f0216192ab)
   




