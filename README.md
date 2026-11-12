# Sakuku — Catatan Keuangan Pribadi

Web pencatat keuangan yang cukup diisi dengan kalimat biasa, misalnya:

> beli cilok 5rb pake cash

Kategori, jumlah, sumber dana (Cash, GoPay, DANA, bank, dll.), tanggal, dan jam langsung tercatat otomatis.

## Fitur

- **Catat dengan kalimat**: satu kalimat bisa berisi beberapa transaksi, paham bahasa santai ("goceng", "1,5jt", "tadi pagi", "kemarin").
- **Tiga jenis transaksi**: pengeluaran, pemasukan, dan pindah dana (top up e-wallet, tarik tunai).
- **Saldo per sumber** dan total saldo.
- **Laporan harian, mingguan, dan bulanan**:
  - grafik pemasukan vs pengeluaran per hari (mingguan) dan per pekan (bulanan),
  - tren 6 bulan terakhir,
  - ringkasan otomatis, rincian per kategori, dan tabel angka.
- Ubah atau hapus transaksi, catat manual, dan salin data sebagai CSV.
- Tampilan untuk HP, dengan mode gelap otomatis.

## Cara menjalankan

Semua kode ada di satu file, `index.html`.

- **Sebagai artifact Claude (fitur lengkap)**: Claude membaca kalimat, data tersimpan di akun Claude, dan input suara aktif.
- **Dibuka langsung / GitHub Pages (mode offline)**: data tersimpan di browser (localStorage) dan kalimat dibaca dengan aturan sederhana. Cocok untuk mencoba, tapi data hanya ada di perangkat itu.

Untuk GitHub Pages: buka **Settings → Pages**, pilih branch `main` dan folder `/ (root)`.
