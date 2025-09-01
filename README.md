🍴 Dapur Tini

Website pemesanan makanan rumahan berbasis PHP & MySQL dengan tampilan modern menggunakan Bootstrap.
Proyek ini dikembangkan sebagai solusi digital untuk mempermudah pelanggan dalam memesan makanan secara online.

🚀 Fitur Utama

✅ Halaman Katalog Produk

Menampilkan daftar makanan dengan gambar, harga, dan status ketersediaan.

Fitur filter kategori (contoh: lauk, sayur, kue).

Tombol Pesan Sekarang untuk menambahkan ke keranjang.

✅ Halaman Checkout

Formulir input data pembeli (nama, alamat, kecamatan, no. HP).

Upload bukti pembayaran.

Menampilkan ringkasan pesanan sebelum dikirim.

✅ Halaman Admin

Tambah produk baru (dengan gambar, kategori, status).

Edit & hapus produk.

Melihat daftar pesanan pelanggan.

✅ Struk / Nota Pesanan

Setelah checkout, sistem otomatis membuat nota pesanan.

🛠️ Teknologi yang Digunakan

Frontend: HTML5, CSS3, Bootstrap 5

Backend: PHP 8, MySQL

Database: MySQL dengan tabel produk & pesanan

Tools: XAMPP / Laragon (local server)

📂 Struktur Folder
Dapur-Tini/
│── assets/        # gambar, css, js
│── admin/         # halaman admin
│── checkout.php   # halaman checkout
│── nota.php       # struk pesanan
│── index.php      # katalog produk
│── db.sql         # database
│── README.md

⚡ Instalasi & Menjalankan

Clone repo ini:

git clone https://github.com/Kaylahahla/Dapur-Tini.git


Pindahkan folder ke dalam direktori server (misalnya htdocs kalau pakai XAMPP).

Import database:

Buka phpMyAdmin → buat database baru → import file db.sql.

Jalankan server Apache & MySQL.

Akses di browser:

http://localhost/Dapur-Tini

🖼️ Screenshot

(tambahkan screenshot hasil tampilan website di sini, misalnya katalog produk & checkout)

👩‍💻 Developer

Proyek ini dikembangkan oleh Kaylahahla sebagai bagian dari tugas kuliah & portfolio web development.
