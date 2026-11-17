# 💧 Keuangan Queen Water

Aplikasi web sederhana untuk mencatat pemasukan & pengeluaran Queen Water.
Data awal diambil dari `pemasukan_uang_queen_water.xlsx` (21 transaksi, total masuk Rp 570.000, keluar Rp 337.000, saldo Rp 233.000).

Fitur: tambah/edit/hapus transaksi, saldo berjalan otomatis, filter bulan/tempat/pencarian, grafik harian, rekap per tempat, unduh CSV, backup & pulihkan JSON. Data tersimpan di browser (localStorage), tanpa server.

## Cara pasang di GitHub Pages
1. Buat repository baru di GitHub, misalnya `queen-water`.
2. Upload semua file ini (`index.html`, `README.md`, folder `.github`).
3. Buka **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Setiap push ke branch `main` akan otomatis ter-deploy.
5. Alamat: `https://<username>.github.io/queen-water/`

> Data tersimpan per perangkat/browser. Gunakan **Backup JSON** secara berkala.
