# Dompet Mikail - Financial & Budget Dashboard

Dashboard interaktif perencanaan keuangan pribadi, analisis pengeluaran harian, alokasi anggaran, dan komparasi bulanan dengan antarmuka modern yang terinspirasi dari spreadsheet eksekutif.

## 🚀 Fitur Utama

- **Total Pemasukan, Total Pengeluaran, & Sisa Saldo**: Kartu KPI warna-warni yang menghitung metrik keuangan secara otomatis beserta perbandingan persentase terhadap bulan lalu.
- **Total Transaksi**: Menghitung volume transaksi bulanan dengan indikator tren.
- **Grafik Pengeluaran Harian**: Grafik spline area interaktif yang menampilkan dinamika pengeluaran dari tanggal 1 hingga akhir bulan lengkap dengan tooltip dan nilai puncak.
- **Alokasi Anggaran (Donut Chart)**: Visualisasi proporsi pengeluaran per kategori (Kebutuhan Rumah Tangga, Investasi & Tabungan, Pribadi, Kesehatan, Pendidikan, Hiburan, dll) dengan persentase real-time.
- **Pengeluaran Bulan Ini vs Bulan Lalu**: Tabel perbandingan pengeluaran antar subkategori dengan indikator naik/turun (`▲` / `▼`).
- **Rangking 21 Pengeluaran Tertinggi**: Tabel terurut dari pengeluaran terbesar untuk mempermudah evaluasi pos pengeluaran prioritas.
- **Smart Mini Reports**: Analisis teks dinamis yang mengevaluasi sisa saldo dan memberikan saran keuangan.
- **Input & Target Budget**: Fitur penetapan budget bulanan dengan visualisasi progress bar rasio pemasukan vs pengeluaran.
- **Penyimpanan Lokal (LocalStorage)**: Transaksi baru tersimpan secara otomatis di peramban tanpa perlu database eksternal.
- **Ekspor CSV**: Kemampuan mengekspor riwayat transaksi ke format file spreadsheet CSV.

## 💻 Menjalankan Secara Lokal

Buka file `index.html` langsung di peramban web apa saja (Chrome, Edge, Firefox), atau jalankan server lokal:

```bash
# Menggunakan Python
python -m http.server 8000

# Atau menggunakan Node.js
npx serve .
```

Kemudian akses: `http://localhost:8000`

## 🌐 Deployment Netlify

Proyek ini sudah dilengkapi konfigurasi `netlify.toml` untuk deployment instan di [Netlify](https://www.netlify.com/):
1. Hubungkan repository GitHub `dompet-mikail` ke Netlify.
2. Publish directory: `.` (root).
3. Selesai! Website langsung aktif.
