# E-Commerce

# Mahasiswa

```bash
    Nama : Muhammad Fiqri Sanusi
    NIM  : 2241012
```

## Screenshots

### Halaman Admin

![preview img](/preview.png)

### Halaman E-Commerce

![preview img](/preview2.png)

### Halaman Kategori Makanan

![preview img](/preview3.png)

### Halaman Kategori Pakaian

![preview img](/preview4.png)

### Halaman Transaksi

![preview img](/preview5.png)

## Setting XAMPP

```bash
-  Masuk File php.ini
-  hapus ( ; ) dalam extension gd
-  Jalankan Apache dan Mysql pada XAMPP
```

## Inisialisasi Projek

Clone Projek

```bash
  git clone https://github.com/mfsfiqri/2241012_UAS_Laravel.git
```

Masuk ke folder dengan perintah

```bash
  cd 2241012_UAS_Laravel
```

Copy .env.example menjadi .env

Edit nama database sesuai keinginan dalam file .env

Install nodejs

```bash
    npm install
```

Install composer pada projek

```bash
    composer install
```

Mengatur kunci(key) baru untuk .env

```bash
    php artisan key:generate
```

Mengapus semua tabel di tabase dan jalankan migrasi untuk tabel baru, lalu isi tabel tersebut dengan data dummy menggunakan seeder

```bash
    php artisan artisan migrate:fresh --seed
```

Buat symbolic link agar file yang diunggah bisa di akses melalui web

```bash
    php artisan storage:link
```

Untuk menjalankan dashboard admin

```bash
    npm run dev
```

menjalankan server laravel e-commerce

```bash
    php artisan serve
```

#### Login Halaman Admin Utama

-   http://127.0.0.1:8000/admin/dashboard
-   produk-produk harus diisi manual karena tadi kita menjalankan perintah migrate:fresh

#### Login Halaman Utama

-   http://127.0.0.1:8000

#### Login

-   email = admin@admin.com
-   password = 123
