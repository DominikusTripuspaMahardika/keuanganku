# KeuanganKu – Smart Finance Tracker

KeuanganKu adalah aplikasi pencatatan keuangan pribadi **front-end only** yang modern, profesional, dan responsif. Aplikasi ini dirancang dengan pendekatan **offline-first**, seluruh data disimpan secara lokal menggunakan **IndexedDB**, tanpa backend, tanpa API eksternal, dan tanpa server.

Aplikasi berjalan **100% di sisi klien** dan tetap berfungsi meskipun tanpa koneksi internet.

---

## ✨ Fitur Utama

- 📊 Dashboard ringkasan keuangan realtime
- 💰 Manajemen Pemasukan & Pengeluaran (tambah, edit, hapus)
- 🎯 Target Keuangan dengan progress otomatis
- 📈 Statistik keuangan & per kategori
- 🗂️ Manajemen kategori Income & Expense
- 🎨 10 tema visual modern (realtime switch)
- 💾 Penyimpanan data lokal menggunakan IndexedDB
- 📱 Responsif untuk desktop & mobile
- 🌐 Offline-first (tanpa koneksi internet)

---

## 🧱 Teknologi yang Digunakan

- **HTML5**
- **CSS3 (Modern + CSS Variables)**
- **JavaScript (Vanilla / Murni)**
- **IndexedDB** untuk penyimpanan data
- **Font Awesome (versi lengkap)** untuk icon
- **SVG** untuk efek visual dan animasi ringan

---

## 📱 Responsivitas & Navigasi

- **Desktop**: Sidebar navigation
- **Mobile**: Bottom navigation
- Navigasi aktif otomatis
- Animasi transisi halus antar halaman
- Loading animation realtime saat:
  - Aplikasi dibuka
  - Berpindah halaman
  - Memuat data dari IndexedDB

---

## 💰 Sistem Transaksi

Setiap transaksi memiliki:
- Tipe: `income` atau `expense`
- Nominal (wajib > 0)
- Kategori
- Tanggal
- Deskripsi (opsional)

### Aturan Penting:
- Saldo awal = **0**
- Semua pemasukan **menambah saldo**
- Semua pengeluaran **mengurangi saldo**
- Tambah, edit, atau hapus transaksi **selalu memicu perhitungan ulang**
- Saldo yang ditampilkan adalah **saldo bersih 100%**

---

## 🗂️ Manajemen Kategori

- Kategori **Income** dan **Expense** terpisah
- Minimal **30 kategori bawaan** masing-masing
- Setiap kategori memiliki **icon & warna**
- Tambah kategori dengan:
  - Semua icon gratis **Font Awesome**
  - **50 warna unik** (tanpa duplikasi)
- Kategori yang **sudah digunakan tidak bisa diedit atau dihapus**
- Sistem otomatis mendeteksi keterkaitan kategori dengan transaksi
- Urutan kategori dapat diatur (drag & drop / naik–turun)
- Urutan kategori memengaruhi dropdown transaksi

---

## 🎯 Target Keuangan

Fitur target keuangan mencakup:
- Nama target
- Nominal target
- Tanggal mulai & selesai
- Status aktif / selesai
- Progress otomatis berbasis transaksi

### Logika Target:
- Progress dihitung **realtime dari transaksi pemasukan**
- Target **tidak menyimpan progress manual**
- Pengeluaran **tidak mengurangi progress target**
- Target aktif ditampilkan di Dashboard
- Peringatan otomatis muncul **3 hari sebelum target berakhir**
- Target selalu sinkron dengan data transaksi

---

## 📈 Statistik

- Total pemasukan
- Total pengeluaran
- Saldo bersih
- Grafik sederhana
- Statistik per kategori
- Seluruh data diambil langsung dari IndexedDB
- Tampilan statistik menyesuaikan tema aktif

---

## 🎨 Tema Visual

Tersedia **10 tema visual**:
1. Light Clean  
2. Dark Pro  
3. Midnight Blue  
4. Cyber Neon  
5. Emerald Finance  
6. Sunset Orange  
7. Royal Purple  
8. Ocean Aqua  
9. Earth Brown  
10. Rose Pink  

### Karakteristik Tema:
- Menggunakan **CSS Variables**
- Tidak ada warna hard-coded
- Preview tema sebelum diterapkan
- Perubahan tema realtime
- Disimpan secara lokal

---

## ⚙️ Pengaturan & Manajemen Data

- Pengaturan tema visual
- Manajemen data:
  - Export data
  - Import data
  - Hapus seluruh data
- Pada bagian Manajemen Data, tombol **hanya berupa icon tanpa teks**

---

## 📁 Struktur Penamaan

- Prefix **class dan id**:


- Struktur kode modular dan konsisten
- Mudah dikembangkan dan dipelihara

---

## 🚫 Batasan

- Tidak menggunakan backend
- Tidak menggunakan API eksternal
- Tidak menggunakan database server
- Tidak memerlukan API Key
- Seluruh data bersifat lokal (client-side only)

---

## 📜 Lisensi

Proyek ini bersifat **open-source** dan dapat digunakan untuk keperluan pembelajaran maupun pengembangan pribadi.

---

## 🙌 Penutup

KeuanganKu dirancang sebagai aplikasi keuangan pribadi yang **jujur secara logika**, **akurat dalam perhitungan**, dan **nyaman digunakan**, dengan fokus pada performa, kejelasan data, dan pengalaman pengguna.

