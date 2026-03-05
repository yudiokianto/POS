# POS Sederhana Ayam Bakar

Aplikasi Point of Sale sederhana berbasis HTML, CSS, dan JavaScript untuk membantu usaha ayam bakar.

## Fitur

- Layout dengan **side panel** untuk navigasi antar halaman.
- Halaman **Data Customer** untuk tambah dan kelola customer.
- Halaman **Stok Produk** untuk tambah produk, lihat stok, tambah stok, dan hapus produk.
- Halaman **Proses Penjualan** untuk transaksi berdasarkan customer + produk.
- Validasi stok agar penjualan tidak melebihi stok tersedia.
- Riwayat transaksi dan ringkasan total omzet.
- Penyimpanan data lokal menggunakan `localStorage`.

## Cara Menjalankan

Cukup buka `index.html` langsung di browser, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Lalu akses: `http://localhost:8000`
