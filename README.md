<h1 align="center">Sakukurata</h1>

<p align="center">
  <strong>Aplikasi Pencatat & Pelacak Keuangan Pribadi</strong>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/php-8.3+-purple.svg" alt="PHP"></a>
  <a href="#"><img src="https://img.shields.io/badge/laravel-13.x-red.svg" alt="Laravel"></a>
</p>


  ```bash
  # link demo
  https://sakukurata-two.vercel.app/

  # akun demo
  email: test2@example.com
  password: 12345678

  #link penjualan
  
  ```

---

## Deskripsi

**Sakukurata** adalah aplikasi web pencatat keuangan pribadi yang dibangun dengan Laravel. Aplikasi ini membantu kamu untuk:

- **Mencatat transaksi** - Pemasukan, pengeluaran, piutang, dan pelunasan secara cepat
- **Mengalokasikan anggaran** - Batasi pengeluaran per kategori (makanan, transportasi, hiburan, dll)
- **Menentukan target tabungan** - Tetapkan goal dan pantau progres tabunganmu
- **Melihat analisis keuangan** - Grafik visual untuk memahami ke mana uangmu mengalir
- **Mengelola pengaturan** - Kategori custom dan preferensi personal

---

## Tech Stack

- **Backend:** Laravel 13.x / PHP 8.3+
- **Frontend:** Blade Templates / Tailwind CSS 4.x
- **Build Tool:** Vite 8.x

---

## Instalasi

### Prasyarat

- PHP >= 8.3
- Composer
- Node.js & npm
- SQLite atau MySQL

### Cara Install

```bash
# 1. Clone repository
git clone https://github.com/SyafiqIkhsan/sakukurata.git
cd sakukurata

# 2. Install dependencies
composer install

# 3. Setup environment
cp .env.example .env
php artisan key:generate

# 4. Buat database SQLite
touch database/database.sqlite

# 5. Jalankan migrasi & seed
php artisan migrate
php artisan db:seed

# 6. Install dependencies frontend & build
npm install
npm run build

# 7. Jalankan server
php artisan serve
```

Buka `http://localhost:8000` di browser.

> **Tips:** Kamu juga bisa menjalankan `composer setup` untuk menjalankan seluruh langkah di atas secara otomatis.

---

## License

Project ini dilisensikan di bawah **MIT License** - lihat file [LICENSE](LICENSE) untuk detailnya.
