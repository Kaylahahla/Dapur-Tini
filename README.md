# 🍽️ Dapur Tini - Website Pemesanan Makanan Rumahan

Website ini dibuat untuk mendukung usaha **Dapur Tini**, sebuah layanan makanan rumahan yang dapat dipesan secara online.  
Fitur utama meliputi katalog produk, pemesanan makanan, checkout dengan bukti pembayaran, serta halaman admin untuk manajemen produk.

---

## 🚀 Fitur Utama

- ✅ **Katalog Produk**: Menampilkan daftar menu dengan filter kategori.  
- ✅ **Status Produk**: Menampilkan status ketersediaan (Ready / Tidak Ready).  
- ✅ **Pesan Sekarang**: Tombol untuk melakukan pemesanan langsung.  
- ✅ **Checkout**: Form pengisian data pelanggan dan upload bukti pembayaran.  
- ✅ **Struk Pesanan**: Menampilkan ringkasan pesanan setelah checkout.  
- ✅ **Halaman Admin**: CRUD produk (tambah, edit, hapus, ubah status, upload gambar).  

---

## 🛠️ Teknologi yang Digunakan

- **Frontend**: Bootstrap 5, HTML, CSS, JavaScript  
- **Backend**: PHP (Native)  
- **Database**: MySQL  


/dapur-tini
│── /assets # File CSS, JS, dan gambar
│── /config # Koneksi database
│── /includes # Header, footer, komponen umum
│── /admin # Halaman admin (CRUD produk & manajemen)
│── index.php # Halaman utama (katalog produk)
│── produk.php # Halaman daftar produk
│── checkout.php # Form checkout & upload bukti pembayaran
│── proses_checkout.php # Proses penyimpanan pesanan ke database
│── struk.php # Ringkasan struk pesanan
│── login.php # Login admin
│── dashboard.php # Dashboard admin


