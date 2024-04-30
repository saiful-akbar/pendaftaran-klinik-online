# Aplikasi Pendaftaran Online Pasien di Klinik

## Fitur Utama

- Login Pasien.
- Pemilihan treatment, dokter dan tanggal endpoint untuk pasien.

## Spesifikasi Teknis

- **Backend**: php 8.2 (Laravel 11)
- **Frontend**: Next JS
- **Database**: MySQL 8

## Instalasi Pengembangan

### Backend

- Clone repository

  ```bash
  git clone https://github.com/saiful-akbar/pendaftaran-klinik-online.git && cd pendaftaran-klinik-online/backend

  ```

- Install paket composer

  ```bash
  composer install

  ```

- Copy file `.env` dan generate key

  ```bash
  cp .env.example .env
  php artisan key:generate
  php artisan storage:link

  ```

- Kondigurasi database pada file `.env` dan jalankan migrasi

  ```bash
  php artisan migrate

  ```
