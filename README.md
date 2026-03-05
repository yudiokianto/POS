# POS Sederhana Ayam Bakar

Aplikasi Point of Sale sederhana berbasis HTML, CSS, dan JavaScript untuk membantu usaha ayam bakar.

## Fitur

- Kelola master customer (tambah customer, simpan nama & nomor HP, hapus customer yang belum pernah dipakai transaksi).
- Tambah produk (nama, harga, stok awal).
- Kelola stok produk (tambah stok, hapus produk).
- Proses transaksi penjualan berdasarkan customer dan produk.
- Validasi stok agar penjualan tidak melebihi stok tersedia.
- Riwayat transaksi lengkap (waktu, customer, produk, qty, total) dan ringkasan omzet.
- Penyimpanan data lokal menggunakan `localStorage`.

## Cara Menjalankan

Cukup buka `index.html` langsung di browser, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Lalu akses: `http://localhost:8000`
