# Aplikasi Kasir - PHP Native

Aplikasi kasir sederhana berbasis **PHP Native** dan **MySQL**. Dibuat untuk kebutuhan pengelolaan toko mulai dari input produk, transaksi penjualan, laporan, hingga pengelolaan data pelanggan member.

Saya juga memiliki kemampuan menggunakan **CodeIgniter 4 (CI4)** dan memahami konsep **MVC (Model-View-Controller)**. Untuk project ini saya gunakan **PHP Native** untuk menunjukkan pemahaman konsep dasar.

---


###  Setup Database

1. Buat database baru dengan nama:

```
aplikasi-kasir
```

2. Import file SQL yang sudah tersedia di repository (`aplikasi-kasir.sql`).

### 3️⃣ Konfigurasi Koneksi Database

Buka file `config.php` → sesuaikan dengan pengaturan server lokal Anda:

```php
$host = "localhost";
$user = "root";
$pass = "";
$db = "aplikasi-kasir";
```

### 4️⃣ Jalankan Aplikasi

* Letakkan folder project di **htdocs** (jika menggunakan XAMPP):

```
C:/xampp/htdocs/aplikasi-kasir
```

* Akses via browser:

```
http://localhost/aplikasi-kasir
```

---

## ✅ Fitur Aplikasi

### 1️⃣ Kategori

* Menambahkan, mengedit, dan menghapus kategori produk.

### 2️⃣ Data Produk

* Menambah produk baru → input nama, harga, stok, kategori.
* Edit & hapus produk.

### 3️⃣ Transaksi

* Sistem kasir → pilih produk → masukkan jumlah → **ENTER** → masuk keranjang.
* Tambahkan produk lain → ulangi proses.
* Input uang tunai → otomatis hitung kembalian → **Simpan transaksi**.
* **Fitur informasi pelanggan** → berlaku untuk pelanggan **member**.

### 4️⃣ Data Laporan

* Melihat laporan penjualan yang telah dilakukan.
* Filter berdasarkan periode waktu.

### 5️⃣ User (Member Pelanggan)

* Menambahkan data pelanggan **member** untuk kebutuhan loyalitas pelanggan.

### 6️⃣ Pengaturan

* Mengelola informasi toko (nama toko, alamat, kontak, dll.).

---

## 📄 Struktur Folder

```
/config       → Konfigurasi database
/pages        → Halaman utama aplikasi
/kategori     → Modul kategori produk
/produk       → Modul data produk
/transaksi    → Modul transaksi kasir
/laporan      → Modul laporan penjualan
/member       → Modul data pelanggan member
/pengaturan   → Modul informasi toko
```

---

## 👨‍💻 Teknologi yang Digunakan

* PHP Native
* MySQL
* HTML, CSS (Bootstrap 5)
* JavaScript (Vanilla JS)

---

## 📌 Catatan Tambahan

Project ini dapat dikembangkan lebih lanjut menggunakan **CodeIgniter 4 (CI4)** untuk penerapan konsep **MVC** yang lebih rapi dan terstruktur.

---

© Zainul Adensyah
