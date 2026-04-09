# BookStoreKay - Toko Buku Online

Selamat datang di BookStoreKay, sebuah aplikasi toko buku online yang modern, lengkap dengan fitur autentikasi, keranjang belanja, berbagai metode pembayaran, dan dashboard admin.

## 🚀 Fitur Utama

### 👥 Autentikasi & Akun
- ✅ Halaman login dengan validasi
- ✅ Halaman pendaftaran akun baru
- ✅ Sistem role (User & Admin)
- ✅ Profile pengguna
- ✅ Riwayat pesanan

### 📚 Manajemen Buku
- ✅ Katalog buku dengan 8+ judul
- ✅ Filter by kategori & pencarian
- ✅ Tampilan detail buku dengan rating
- ✅ Info stok real-time
- ✅ Dashboard admin untuk kelola buku

### 🛒 Sistem Belanja
- ✅ Keranjang belanja interaktif
- ✅ Tambah/kurangi jumlah item
- ✅ Hitung subtotal + pajak otomatis
- ✅ Checkout dengan form alamat
- ✅ Pilihan pengiriman (Standar, Express, Overnight)

### 💳 Metode Pembayaran
- ✅ Kartu Kredit/Debit
- ✅ Transfer Bank
- ✅ E-Wallet (GoPay, OVO, Dana, LinkAja)
- ✅ Cicilan 0% (3, 6, 12 bulan)

### 📢 Fitur Tambahan
- ✅ Running text banner beranda
- ✅ Sistem notifikasi real-time
- ✅ **Notifikasi pembayaran lengkap** (pending, konfirmasi, berhasil, gagal, reminder)
- ✅ Dashboard admin dengan konfirmasi pembayaran manual
- ✅ Dark theme responsive design
- ✅ Footer dengan social links
- ✅ Newsletter subscription

### 👨‍💼 Admin Panel
- ✅ Dashboard statistik
- ✅ Manajemen buku
- ✅ Manajemen pesanan
- ✅ Manajemen pengguna

## 📋 Akun Demo

### User Account
- **Email:** user@example.com
- **Password:** user123

### Admin Account
- **Email:** admin@bookstore.com
- **Password:** admin123

Anda juga bisa membuat akun baru dengan fitur register.

## 🛠️ Instalasi & Setup

### Persyaratan
- Browser modern (Chrome, Firefox, Safari, Edge)
- Koneksi internet

### Langkah Instalasi

1. **Clone atau download project**
   ```bash
   git clone https://github.com/your-username/BookStoreKay.git
   cd BookStoreKay
   ```

2. **Buka di browser**
   - Langsung buka file `index.html` dengan double-click
   - Atau gunakan Live Server di VS Code

3. **Mulai berbelanja!**
   - Register akun baru atau gunakan akun demo
   - Browse buku dan tambahkan ke keranjang
   - Checkout dengan memilih metode pembayaran

## 📁 Struktur Folder

```
BookStoreKay/
├── index.html          # Halaman utama
├── styles.css          # Styling
├── script.js           # Logika aplikasi
├── README.md           # Dokumentasi ini
├── DATABASE.md         # Struktur data
└── GITHUB.md           # Panduan GitHub
```

## 🗄️ Data Storage

Aplikasi menggunakan **localStorage** untuk menyimpan:
- Data pengguna
- Keranjang belanja
- Histori pesanan
- Daftar buku

Data disimpan secara lokal di browser Anda.

## 🌐 Fitur GitHub Integration

### Link GitHub
Footer aplikasi mencantumkan link GitHub:
- Repository link aktif di pengunjung web
- Social media links (GitHub, Instagram, Facebook, Twitter)

### Cara Setup GitHub Repository
1. Buat repository baru di GitHub
2. Push code ke repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - BookStoreKay"
   git remote add origin https://github.com/your-username/BookStoreKay.git
   git push -u origin main
   ```

3. Update footer dengan username GitHub Anda:
   - Edit `index.html`, cari "your-username"
   - Ganti dengan username GitHub Anda

## 💰 Metode Pembayaran - Detail

### 1. Kartu Kredit/Debit
- Masukkan nomor kartu 16 digit
- Bulan/Tahun (MM/YY)
- CVV 3 digit
- Nama di kartu

### 2. Transfer Bank
- Nomor rekening: 1234567890
- Bank: BCA
- Atas Nama: PT BookStoreKay
- Instruksi pembayaran ditampilkan di halaman

### 3. E-Wallet
- GoPay, OVO, Dana, LinkAja
- Scan QR atau transfer langsung
- Instant confirmation

### 4. Cicilan
- 0% untuk semua tenor
- 3 bulan, 6 bulan, atau 12 bulan
- Cicilan otomatis dihitung

## 📧 Notifikasi Pembayaran

Sistem notifikasi pembayaran yang komprehensif:
- ✅ **Notif pembayaran pending** - Saat pembayaran sedang diproses
- ✅ **Notif menunggu konfirmasi** - Transfer bank menunggu verifikasi admin
- ✅ **Notif pembayaran berhasil** - Konfirmasi pembayaran diterima
- ✅ **Notif pembayaran gagal** - Pembayaran ditolak atau error
- ✅ **Notif reminder pembayaran** - Pengingat untuk pembayaran tertunda
- ✅ **Notif status pesanan** - Update status pengiriman
- ✅ **Dashboard admin** - Konfirmasi manual pembayaran transfer bank
- ✅ Toast notifications yang elegan dengan ikon dan warna berbeda

### Fitur Admin untuk Pembayaran:
- 👀 **Monitoring status pembayaran** - Lihat semua status pembayaran real-time
- ✅ **Konfirmasi pembayaran** - Tombol konfirmasi untuk transfer bank
- ❌ **Tolak pembayaran** - Opsi menolak pembayaran yang tidak valid
- 📊 **Laporan pembayaran** - Statistik pembayaran di dashboard

## 📊 Dashboard Admin

Hanya akun dengan role "admin" yang bisa akses:
- **Statistik**: Total order, user, buku, revenue
- **Kelola Buku**: Edit/hapus buku
- **Kelola Pesanan**: Update status pengiriman
- **Kelola Pengguna**: Lihat daftar pengguna

## 🎨 Tema & Design

- Warna Utama: #2c3e50 (Dark Blue-Gray)
- Warna Sekunder: #e74c3c (Red)
- Warna Accent: #3498db (Blue)
- Responsive design untuk semua ukuran layar

## 🔒 Keamanan

⚠️ **PERHATIAN**: Ini adalah demo aplikasi. Untuk production:
- Gunakan backend server (Node.js, PHP, Python, dll)
- Implementasi proper authentication (JWT, OAuth)
- Encrypt password
- SSL/HTTPS
- Database server (MySQL, PostgreSQL, MongoDB)
- Payment gateway integration (Stripe, PayPal, dll)

## 🚀 Deployment

### Option 1: GitHub Pages
```bash
# Push ke branch gh-pages
git push origin main:gh-pages
```

### Option 2: Netlify
1. Connect repository ke Netlify
2. Set build command (jika ada)
3. Deploy otomatis

### Option 3: Vercel
1. Upload project ke Vercel
2. Deployment otomatis

## 📱 Responsive Design

- ✅ Desktop (1200px+)
- ✅ Tablet (768px - 1199px)
- ✅ Mobile (< 768px)

## 🐛 Known Issues & TODO

- [ ] Edit profil user
- [ ] Tambah buku baru (admin)
- [ ] Upload foto buku
- [ ] Rating & review
- [ ] Wishlist
- [ ] Tracking pengiriman
- [ ] Chat support

## 🤝 Kontribusi

Kontribusi sangat diterima!

```bash
1. Fork repository
2. Buat branch fitur (git checkout -b feature/AmazingFeature)
3. Commit changes (git commit -m 'Add some AmazingFeature')
4. Push ke branch (git push origin feature/AmazingFeature)
5. Open Pull Request
```

## 📄 Lisensi

Project ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail.

## 👨‍💻 Author

**BookStoreKay Development Team**
- 📧 Email: nawfalzainkaysan@gmail.com
- 🐙 GitHub: [BookStoreKay](https://github.com/your-username)
- 📱 Instagram: [@bookstorkay](https://www.instagram.com/zaniwuthering/)

## 🙏 Terima Kasih

Terima kasih telah menggunakan BookStoreKay! Semoga aplikasi ini bermanfaat untuk pembelajaran web development.

---

**Last Updated**: April 2026
**Version**: 1.0.0

Jangan lupa untuk star ⭐ repository ini jika bermanfaat! 🚀
# BookStoreKayKA
