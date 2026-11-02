# DC Siborong Borong

**Sistem History Paket Bermasalah + Scan QR + Stok**

Powered by **Amos rcpdroid ~86**

---

## Fitur

### 📦 History Paket Bermasalah
- Tambah / Edit / Hapus
- Jenis masalah + status
- Filter & pencarian
- **Foto paket** (kamera HP)

### 📷 Scan QR / Barcode
- Scan langsung dari kamera HP
- Ambil nomor resi otomatis
- Coba ambil data dari **SPX Express** (public)
- Tombol buka situs resmi SPX jika API terhalang CORS

### 📋 Data Stok
- Nama, jumlah, satuan, lokasi

### 📊 Laporan
- Ringkasan jumlah per status
- Jumlah per jenis masalah
- **Export CSV**

### PWA
- Bisa di-install di HP
- Offline support (data lokal)

---

## Cara Upload ke GitHub Pages

1. Buat repository baru di GitHub (public)
2. Upload semua file di folder ini (drag & drop)
3. Settings → Pages → Source: Deploy from branch `main` / root
4. Tunggu 1-2 menit
5. Buka: `https://USERNAME.github.io/NAMA-REPO/`

## Install di HP
Buka di Chrome → menu ⋮ → **Add to Home screen** / Install app

## Catatan SPX
API publik SPX sering memblokir request dari domain lain (CORS).  
Aplikasi tetap menyimpan resi hasil scan, dan ada tombol **Buka SPX resmi** untuk cek status di situs asli.

Data disimpan di **LocalStorage browser** perangkat.  
Hapus cache browser = data hilang. Backup dengan Export CSV secara berkala.
