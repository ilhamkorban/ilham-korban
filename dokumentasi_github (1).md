# Concept Website UMKM - Kopi Nusantara

Proyek ini adalah rancangan dan implementasi awal *Landing Page* sederhana untuk UMKM **Kopi Nusantara**.

---

## 🛠️ 1. Arsitektur Web

Website ini menggunakan konsep **Single-Page Application (SPA)** sederhana untuk memudahkan navigasi pembeli tanpa perlu berpindah halaman.

```text
[ Landing Page (index.html) ]
       │
       ├──> [ Navbar ] ───────> Navigasi (Beranda, Produk, Kontak)
       │
       ├──> [ Hero Section ] ──> Banner Utama & Call-to-Action (CTA)
       │
       ├──> [ Katalog ] ──────> Produk Unggulan & Tombol Beli
       │
       └──> [ Direct Link ] ──> Integrasi Transaksi via WhatsApp API
```

---

## 👤 2. User Story

Berikut alur interaksi pengguna saat menjelajahi situs ini:

1. **Eksplorasi Awal (*Hero Section*):**
   * Pengguna masuk ke halaman utama dan langsung memahami produk yang ditawarkan melalui tagline dan visual banner.
2. **Melihat Katalog Produk:**
   * Pengguna melakukan *scroll* ke bawah untuk melihat daftar produk unggulan beserta deskripsi dan harga.
3. **Melakukan Pemesanan:**
   * Pengguna memilih produk dan mengklik tombol **"Beli Sekarang"**.
   * Pengguna secara otomatis diarahkan ke akun WhatsApp penjual dengan pesan otomatis sesuai produk yang dipilih.

---

## 🚀 Cara Menjalankan Secara Lokal

1. Unduh atau *clone* repositori ini:
   ```bash
   git clone https://github.com/username/website-umkm.git
   ```
2. Buka berkas `index.html` di browser favorit Anda.