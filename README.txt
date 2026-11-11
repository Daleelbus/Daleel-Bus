BUS INDONESIA — PROTOTIPE WEB

Isi:
- index.html: aplikasi web
- manifest.webmanifest dan sw.js: dukungan PWA dasar

Cara mencoba:
1. Ekstrak ZIP.
2. Buka index.html di browser untuk uji tampilan dasar.
3. Untuk memasang sebagai PWA, unggah seluruh isi folder ke hosting HTTPS.
4. Buka URL hosting melalui Chrome Android > menu ⋮ > Tambahkan ke layar utama / Install aplikasi.

Catatan penting:
- Data awal berasal dari PDF BUS DALEEL 9 nov 2026.
- Prototipe menyimpan perubahan pada localStorage browser/perangkat yang digunakan.
- Ini BELUM merupakan sistem online multi-pengguna. Pemesanan pelanggan belum terkirim ke admin di perangkat lain.
- Untuk produksi perlu backend/database, login admin, validasi pembayaran, dan perlindungan data.
- Kolom status pembayaran pada PDF tidak ditafsirkan; baris lama diberi label Data PDF.
