# Kopi Keseduh — Online Coffee Store

Website katalog dan pemesanan online untuk **biji kopi utuh** serta **kopi bubuk siap seduh**.

## Menjalankan website
1. Extract folder `kopi-keseduh`.
2. Buka folder di Visual Studio Code.
3. Jalankan `index.html` dengan ekstensi Live Server, atau buka langsung di browser.

## Fitur
- Tema dark coffee premium yang responsif untuk desktop dan ponsel.
- Katalog produk biji kopi dan kopi bubuk.
- Filter jenis produk, pencarian, dan pengurutan harga.
- Detail produk, keranjang belanja, ubah jumlah, dan subtotal.
- Keranjang tersimpan di browser menggunakan localStorage.
- Checkout dan formulir kontak membuat pesan WhatsApp otomatis.

## Pengaturan sebelum dipublikasikan
- Buka `script.js`, ubah `WA_NUMBER` menjadi nomor WhatsApp toko dengan format internasional tanpa tanda `+` (contoh format: `62812...`).
- Periksa nama produk, asal kopi, deskripsi, berat, foto, dan harga pada array `products` di `script.js`. Data produk/harga saat ini adalah contoh awal dan harus disesuaikan dengan stok serta harga tokomu.
- Ganti akun Instagram dan jam layanan pada `index.html` jika diperlukan.
- Foto produk pada katalog inventori disimpan lokal di folder `assets` agar tetap tampil tanpa koneksi ke server gambar eksternal. Ganti dengan foto produk asli bila tersedia.

## Catatan
Website ini menyiapkan alur katalog, keranjang, dan checkout melalui WhatsApp. Pembayaran online otomatis, ongkir real-time, dan manajemen stok belum terhubung ke backend/payment gateway.

## Pembaruan katalog dan foto
- Ikon keranjang diperbarui menjadi ikon cangkir kopi.
- Katalog diisi 6 contoh produk biji kopi dan kopi bubuk.
- Dua foto kemasan dari pemilik website dipakai sebagai referensi visual produk pertama dan kedua.
- Empat foto kemasan produk lainnya sudah disediakan sebagai aset lokal agar gambar katalog tidak bergantung pada tautan eksternal.
- Nama, berat, deskripsi, dan harga keenam produk adalah contoh awal; sesuaikan dengan stok dan harga jual sebenarnya.
