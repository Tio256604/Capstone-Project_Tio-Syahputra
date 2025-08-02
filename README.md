Coffee Sales Analysis – Capstone Project_Tio Syahputra

Project Overview
Proyek ini bertujuan menganalisis data penjualan kopi menggunakan bantuan AI untuk menggali insight yang bermakna dan menghasilkan rekomendasi strategis. Data yang dianalisis mencakup informasi jenis kopi, waktu pembelian, metode pembayaran, serta pendapatan per bulan.
Analisis dilakukan menggunakan Python di Google Colab, dan dukungan model AI IBM Granite untuk membantu menyusun insight dan rekomendasi. Visualisasi data juga digunakan untuk memperkuat interpretasi hasil.

Raw Dataset Link
> [Coffe_sales.xlsx]

Insight & Findings

1. Produk terlaris: 
   Americano with Milk dan Latte mendominasi penjualan dan pendapatan.
2. Waktu dan hari transaksi tertinggi:
   Terjadi di siang hari (Afternoon) dan awal minggu (Senin–Selasa).
3. Metode pembayaran:
   Mayoritas transaksi (97%) menggunakan kartu (cashless).
4. Pendapatan tertinggi bulanan:
   Terjadi di bulan Maret.  
   Sementara bulan Januari menjadi periode terendah.
5. Hari paling ramai: 
   Hari Selasa mencatat transaksi terbanyak.

Rekomendasi Strategis
- Fokus promosi pada *Americano with Milk* dan *Latte*, termasuk bundling dan topping edisi terbatas.
- Luncurkan diskon atau program loyalti di awal pekan dan jam makan siang.
- Optimalkan pembayaran non-tunai dengan promo cashback khusus (contoh: PayPal, e-wallet).
- Bangun momentum awal tahun (Januari) dengan kampanye “New Year, New Brew”.

AI Support Explanation
Dalam proyek ini, AI berperan sebagai asisten analitik yang digunakan melalui model **IBM Granite 3.3-8B Instruct** via Replicate API.
Fungsi AI:
- Insight Generation: AI digunakan untuk menyusun insight dari data penjualan kopi secara otomatis.
- Recommendation Output: Memberikan rekomendasi bisnis berdasarkan data visualisasi.
- Prompting Teknis: Membantu membuat kode Python untuk tabel klasifikasi dan visualisasi.
Proses ini dijalankan di Google Colab dengan kombinasi eksplorasi data manual dan prompting ke model AI.

Struktur File
- `coffee_analysis.ipynb` → Notebook utama analisis
- `Coffe_sales.xlsx` → Dataset mentah
- `*.png` → Visualisasi pendukung
- `README.md` → Dokumentasi proyek

Author
Tio Syahputra  
Capstone Project – IBM x MySkill  
